---
layout: page
permalink: /teaching/
title: teaching
description: Materials for courses you taught. Replace this text with your description.
nav: true
nav_order: 5
---

{% assign courses = site.data.courses %}

## Instructors

{% for course in courses %}
{% if course.category == "Instructor" %}
### {{ course.name }}

**University:** {{ course.university }}
**Description:** {{ course.description }}

{% endif %}
{% endfor %}

## Teaching Assistants

{% for course in courses %}
{% if course.category == "Teaching Assistant" %}
### {{ course.name }}

**University:** {{ course.university }}
**Description:** {{ course.description }}

{% endif %}
{% endfor %}
