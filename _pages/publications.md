---
layout: page
permalink: /publications/
title: publications
description: publications by categories in reversed chronological order.<br> an up-to-date list is available on <a href="https://scholar.google.com/citations?user=zD5tJIQAAAAJ">Google Scholar</a>.
years: [2021, 2020]
nav: true
---

### conference & journal articles

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

### other theses

<div class="publications">

{% bibliography -f theses %}

</div>
