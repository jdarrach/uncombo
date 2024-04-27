---
layout: searchpage
permalink: /search/
title: Search uncombo
exclude: true
---

<h1>What are you looking for?</h1>

<!-- Html Elements for Search -->
<div id="search-container">
<input type="text" id="search-input" placeholder="Search">
<ul id="results-container"></ul>
</div>

<!-- Script pointing to search-script.js -->
<script src="{{ site.baseurl }}/js/search-script.js" type="text/javascript"></script>

<!-- Configuration -->
<script>
SimpleJekyllSearch({
  searchInput: document.getElementById('search-input'),
  resultsContainer: document.getElementById('results-container'),
  json: '{{ site.baseurl }}/search.json'
})
</script>