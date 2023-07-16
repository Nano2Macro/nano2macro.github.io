---
layout: page
title: Awards
permalink: /awards/
nav: true
nav_order: 6
---

# Awards

{% assign awards = site.data.Awards %}

{% for award in awards %}
- Name: {{ award.name }}
  Source: {{ award.source }}
{% endfor %}
