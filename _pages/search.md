---
layout: default
title: Search
permalink: /search
nav: false
sitemap: false
---

<!-- Import lunr.js from unpkg.com -->
<script src="https://unpkg.com/lunr/lunr.js"></script>

<!-- List where search results will be rendered -->
<ul id="search-results">
Search Results: <br>
</ul>

<!-- Search box -->
<div class="header-search d-flex justify-content-center mt-5 mb-3">
  <form class="header-search-form" action="/search/" method="get">
    <input type="text" id="search-box" name="query">
    <input type="submit" value="search">
  </form>
</div>

<!-- Search Data Stores-->
<script>
  // Template to generate the JSON to search
  // see search.liquid for proper code
  window.store = {
    {% for post in site.posts %}
      {% if post.title != blank and post.content != blank %}
        "{{ post.url | slugify }}": {
            "title": "{{ post.title | xml_escape }}",
            "author": "{{ post.author | xml_escape }}",
            "category": "{{ post.category | xml_escape }}",
            "content": {{ post.content | strip_html | strip_newlines | jsonify }},
            "url": "{{ post.url | xml_escape }}"
        },
      {% endif %}
    {% endfor %}
    {% for post in site.pages %}
      {% if post.title != blank and post.content != blank %}
        "{{ post.url | slugify }}": {
            "title": "{{ post.title | xml_escape }}",
            "author": "{{ post.author | xml_escape }}",
            "category": "{{ post.category | xml_escape }}",
            "content": {{ post.content | strip_html | strip_newlines | jsonify }},
            "url": "{{ post.url | xml_escape }}"
        },
      {% endif %}
    {% endfor %}
  };

</script>

<script>
(function() {
  function showResults(results, store) {
    var searchResults = document.getElementById('search-results');

    if (results.length) { // If there are results...
      var appendString = '';

      for (var i = 0; i < results.length; i++) {  // Iterate over them and generate html
        var item = store[results[i].ref];
        appendString += '<li><a href="' + item.url + '"><h3>' + item.title + '</h3></a>';
        appendString += '<p>' + item.content.substring(0, 250) + '...</p></li>';
      }

      searchResults.innerHTML += appendString;
    } else {
      searchResults.innerHTML += '<li>No results found</li>';
    }
  }

  function getQuery(variable) {
    var query = window.location.search.substring(1);
    var vars = query.split('&');

    for (var i = 0; i < vars.length; i++) {
      var pair = vars[i].split('=');

      if (pair[0] === variable) {
        return decodeURIComponent(pair[1].replace(/\+/g, '%20'));
      }
    }
  }

  /*
   var idx = lunr(function () {
            this.field('id');
            this.field('title', { boost: 10 });
            this.field('author');
            this.field('category');
            this.field('content');
            for (var key in window.store) { 
                this.add({
                    'id': key,
                    'title': window.store[key].title,
                    'author': window.store[key].author,
                    'category': window.store[key].category,
                    'content': window.store[key].content
                });

                
            }
        });

        var results = idx.search(searchTerm); // Get lunr to perform a search
        displaySearchResults(results, window.store); // We'll write this in the next section  
  */
  var searchTerm = getQuery('query');

  if (searchTerm) {
    document.getElementById('search-box').setAttribute("value", searchTerm);

    // Initalize lunr.js with the fields to search.
    // The title field is given more weight with the "boost" parameter
    var idx = lunr(function () {
      this.field('id');
      this.field('title', { boost: 10 });
      this.field('author');
      this.field('category');
      this.field('content');

      for (var key in window.store) { // Add the JSON we generated from the site content to Lunr.js.
        this.add({
          'id': key,
          'title': window.store[key].title,
          'author': window.store[key].author,
          'category': window.store[key].category,
          'content': window.store[key].content
        });
      }
    });

    var results = idx.search(searchTerm); // Perform search with Lunr.js
    showResults(results, window.store);
  }
})();
</script>

