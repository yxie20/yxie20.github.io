---
order_id: 2
layout: page
permalink: /publications/
title: Publications
description: 
years: [2026, 2025, 2022, 2021]
nav: false
---

<div class="publications">

<h2 class="year">Under Review</h2>
{% bibliography -f papers -q @*[status=review]* %}

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
