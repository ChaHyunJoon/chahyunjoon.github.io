---
layout: page
permalink: /publications/
title: publications
description: presentations and publications
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2 class="bibliography">Presentations</h2>
{% bibliography --query @*[category=presentation] --group_by none %}

<h2 class="bibliography">Publications</h2>
{% bibliography --query @*[category=publication] --group_by none %}

</div>
