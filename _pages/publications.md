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
  /* Hide the automatic page title on THIS page only */
  h1 {
    display: none;
  }
</style>

<div class="publications">

## Preprints

{% bibliography
   --query @*[url~=arxiv.org]
   --sort_by year
   --order descending
%}

## Journal publications

{% bibliography
   --query @*[url!~arxiv.org]
   --sort_by year
   --order descending
%}

</div>
</div>
