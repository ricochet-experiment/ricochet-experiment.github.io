---
layout: page
permalink: /publications/
title: Publications
description: Articles from the Ricochet collaboration.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

 {% bibliography --template bib --group_by type,year --group_order ascending,descending %}
 
</div>
