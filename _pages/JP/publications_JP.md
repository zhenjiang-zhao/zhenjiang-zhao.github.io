---
layout: page
permalink: /research_JP/
title: 研究発表
display_lang: JP
description: 
years_publication: [2022]
years_poster: [2023, 2022]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->


### **学会発表**

<div class="publications">

{%- for y in page.years_publication %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f publication_JP -q @*[year={{y}}]* %}
{% endfor %}

</div>


### **ポスター発表・口頭発表**

<div class="publications">

{%- for y in page.years_poster %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f poster_JP -q @*[year={{y}}]* %}
{% endfor %}

</div>
