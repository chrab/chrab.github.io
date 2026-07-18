---
layout: page
permalink: /publications/
title: publications
nav: true
nav_order: 3
---
<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

List of my first author papers. For my full and up-to-date publication list see <a href="https://scixplorer.org/search?p=1&q=docs%28library%2Fq1RMTfMSQUuLqlCQQeHB3g%29&sort=date+desc&d=astrophysics">SciX</a>.

{% include bib_search.liquid %}

<div class="publications">

{% bibliography -f {{ site.scholar.bibliography }} %}

</div>
