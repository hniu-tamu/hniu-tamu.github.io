---
layout: page
permalink: /publications/
title: publications
description: Selected publications by categories in reversed chronological order. For a full list of Haoyu's publication. Please refer to the [Haoyu's Google Scholar](https://scholar.google.com/citations?user=x-xBjiwAAAAJ&hl=en&oi=ao)
years: [2022, 2020, 2021, 1956, 1950, 1935, 1905]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
