---
layout: page
title: "Office Hours / Instructors"
nav_order: 6
description: A listing of all the course staff members.
---

## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}
