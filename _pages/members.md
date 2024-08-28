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
{{ member }}
{% endfor %}

## Research Scientists

## Graduate Students

{% assign members = site.members | where: 'role', 'Graduate Student' %}
{% for member in members %}
{{ member.url }}
{% endfor %}



## Recent Alumni
- foobar
