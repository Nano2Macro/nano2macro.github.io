---
layout: page
title: Awards
permalink: /awards/
nav: true
nav_order: 6
---

{% assign awards = site.data.Awards %}

{% for award in awards %}
{{ forloop.index }}. {{ award.name }}
   {{ award.source }}

{% endfor %}
