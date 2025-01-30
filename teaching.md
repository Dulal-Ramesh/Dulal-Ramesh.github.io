---
layout: page
title: "Courses Taught"
permalink: /teaching/
---
I have been involved in teaching the following courses.
{% for teaching in site.data.courses-taught %}
- **{{ teaching.course }}** – {{ teaching.role }}, {{ teaching.year }}, {{ teaching.institution }}
{% endfor %}
