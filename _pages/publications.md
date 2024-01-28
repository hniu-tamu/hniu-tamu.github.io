---
layout: page
permalink: /publications/
title: publications
description: Selected book and journal publications from <a href='https://scholar.google.com/citations?user=x-xBjiwAAAAJ&hl=en&oi=ao'>Google Scholar</a>. 
years: [2022, 2021, 2020]
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
