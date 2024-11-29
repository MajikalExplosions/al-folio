---
layout: none
title: Redirect
nav: false
nav_order: 100
permalink: /r/
sitemap: false
---

{% include scripts/analytics.liquid %}
<script>
  var query = window.location.search.substring(1);
  var vars = query.split('&');
  var r = "/";
  for (var i = 0; i < vars.length; i++) {
    var pair = vars[i].split('=');

    if (pair[0] === "r") {
        r = decodeURIComponent(pair[1]);
        break;
    }
  }
  location.replace(r);
</script>
