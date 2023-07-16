---
layout: page
title: Awards
permalink: /awards/
nav: true
nav_order: 6
---

# Awards

{% assign awards = site.data.awards %}

{% for award in awards %}
- name: {{ award.name }}
  source: {{ award.source }}
{% endfor %}
