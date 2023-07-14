---
layout: page
permalink: /teaching/
title: teaching
description: Materials for courses you taught. Replace this text with your description.
nav: true
nav_order: 5
---

{% assign courses = site.data.courses %}

{% for course in courses %}
## {{ course.name }}

**Course Code:** {{ course.code }}  
**University:** {{ course.university }}

{{ course.description }}

{% endfor %}
