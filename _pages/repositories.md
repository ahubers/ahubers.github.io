---
layout: page
permalink: /artifacts/
title: artifacts
description: The artifacts listed below accompany some of my publications.
nav: true
nav_order: 3
---

{% if site.data.repositories.artifacts %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.artifacts %}
	{% include repository/repo.html repository=repo %}
  {% endfor %}
</div>
{% endif %}
