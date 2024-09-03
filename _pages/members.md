---
layout: page
permalink: /members/
title: Members
description:
nav: true
nav_order: 1
---

## Professors

{% assign members = site.members | where: 'role', 'Professor' %}
{% for member in members %}
{{ member | slice: 106, 1000 }} <!-- HACK! -->
{% endfor %}

## Research Scientists & Postdoctoral Scholars

{% assign members = site.members | where: 'role', 'Research Scientist' %}
{% for member in members %}
{{ member | slice: 106, 1000 }} <!-- HACK! -->
{% endfor %}


## Graduate Students

{% assign members = site.members | where: 'role', 'Graduate Student' %}
{% for member in members %}
{{ member | slice: 106, 1000 }} <!-- HACK! -->
{% endfor %}



## Recent Alumni
- [Arjun Viswanathan, Ph.D. '24](https://homepage.cs.uiowa.edu/~viswanathn/). *Some college in the Northeast.*
- [Andrew Marmaduke, Ph.D. '24](https://uiowa.marmamorphism.com/#:~:text=Andrew%20Marmaduke). *Postdoctoral scholar at University of Iowa.*
- [Christa Jenkins, Ph.D. '23](https://cwjnkins.github.io/#:~:text=Postdoctoral). *Postdoctoral associate at Stony Brook University.*
- Add more.