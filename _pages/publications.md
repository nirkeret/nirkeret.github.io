---
layout: page
permalink: /publications/
title: Publications
description: publications in reversed chronological order.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

<div class="publications">

### Preprints

{% bibliography
   --query @*[url~=arxiv.org]
   --sort_by year,month
   --order descending
%}

### Journal publications

{% bibliography
   --query @*[url!~arxiv.org]
   --sort_by year,month
   --order descending
%}

</div>
