---
layout: redirect
title: News
nav: true
nav_order: 2
permalink: /r/news
nav_link: /blog/tag/news/
redirect: /blog/tag/news/
sitemap: false
---

{% comment %}
<!-- We don't use news.liquid to render news collection anymore -->
// Instead, we use this file to create a nav link in
// the navabarNav on the top. The only problem is that
// the search module will still take user to the generated
// news site _pages/news .  We force the user to the correct
// /blog/tag/news site by redirect them.
{% include news.liquid %}
{% endcomment %}
