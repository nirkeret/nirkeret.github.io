---
layout: page
permalink: /publications/
title: Publications
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

<style>
  /* Hide the big automatic page title on this page only */
  h1.page-title {
    display: none;
  }
</style>

<div class="publications">

  <h3>Preprints</h3>

  {% bibliography
     --query @*[url~=arxiv.org]
     --sort_by year
     --order descending
  %}

  <h3>Journal Publications</h3>

  {% bibliography
     --query @*[url!~arxiv.org]
     --sort_by year
     --order descending
  %}

</div>
