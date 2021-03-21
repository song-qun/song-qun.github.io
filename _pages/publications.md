---
layout: page
permalink: /publications/
title: Publications
description: 
years: [2021,2019,2018]
nav: true
order: 2
---

### Conferences

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

### Journals