---
layout: page
permalink: /publications/
title: publications
description: 
years: [2019]
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->
<div class="publications">

<!-- {% for y in page.years %} -->
  <!-- <h2 class="year">{{y}}</h2> -->
  {% bibliography -f papers --group_by year %}
<!-- {% endfor %} -->

</div>
