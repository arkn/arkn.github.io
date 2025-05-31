---
layout: page
permalink: /publications/
title: publications
description: 
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2>Peer-reviewed</h2>
{% bibliography --query @*[category=peer-reviewed] %}

<h2>Conference & Workshop (peer-reviewed, abstract)</h2>
{% bibliography --query @*[category=peer-reviewed-abstract] %}

<h2>Patent</h2>
{% bibliography --query @*[category=patent] %}

<h2>Media Coverage</h2>
{% bibliography --query @*[category=media] %}

</div>
