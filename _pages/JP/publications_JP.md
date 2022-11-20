---
layout: page
permalink: /research_JP/
title: 研究発表
display_lang: JP
description: 
years: [2022]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->


### **学会発表**

<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f publication_JP -q @*[year={{y}}]* %}
{% endfor %}

</div>


### **ポスター発表**

<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f poster_JP -q @*[year={{y}}]* %}
{% endfor %}

</div>
