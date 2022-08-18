---
layout: page
permalink: /publications/
title: Research
years_ag: [2021]
years_hci: [2021]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">
<div class="agronomy">
<h1 class="sub_title">Precision Agriculture</h1>
<h2 class="post-description">
  <span>
  The following is the list of publications I was involved in during my Masters degree program in Animal Science at Cornell Nutrient Management Spear Program (<a href = "http://nmsp.cals.cornell.edu">NMSP</a>).
  </span>
</h2>
{%- for y in page.years_ag %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f Agronomy -q @*[year={{y}}]* %}
{% endfor %}
</div>
<h1 class="sub_title">Human Computer Interaction</h1>
<h2 class="post-description">
  <span>
  The following is the list of publications I was involved in during my time as a research assistant for <a href = "https://tech.cornell.edu/people/wendy-ju/">Professor Wendy Ju</a> at Cornell Tech.
  </span>
</h2>
<div class="HCI">
{%- for y in page.years_hci %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f HCI -q @*[year={{y}}]* %}
{% endfor %}
</div>
</div>
