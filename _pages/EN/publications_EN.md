---
layout: page
permalink: /research_EN/
title: Research
display_lang: EN
description: #All my research can be found here.
years_publication: [2024, 2023, 2022]
years_poster: [2024, 2023, 2022]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
### **Publications**

<div class="publications">
{%- for y in page.years_publication %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f publication_EN -q @*[year_o={{y}}]* %}
{% endfor %}
</div>

### **Oral & Poster Presentations**

<div class="publications">
{%- for y in page.years_poster %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f poster_EN -q @*[year={{y}}]* %}
{% endfor %}
</div>
