---
layout: page
permalink: /research_JP/
title: 研究
display_lang: JP
description: All my research can be found here.
years: [2022]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->


### **Publications**

<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f publication_EN -q @*[year={{y}}]* %}
{% endfor %}

</div>


### **Poster Presentation**

<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f poster_EN -q @*[year={{y}}]* %}
{% endfor %}

</div>
