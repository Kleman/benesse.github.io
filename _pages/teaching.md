---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
redirect_from:
  - /teaching
---
I had the opportunity to teach the following courses (following the European Higher Education Area (EHEA) three cycle system, usually referred to as the "LMD" sytem in French.):

- **M2 -- Machine Learning**: Practicals, from 2020 to 2022

- **M1 -- Stochastic Simulations**: Practicals, from 2020 to 2022

- **L3 Biology -- Introduction to Statistics**: Complete course, from 2020 to 2022

- **L1 Computer Science -- Numeric methods**: Practicals, in 2019.

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
