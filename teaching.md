---
layout: page
title: "Courses Taught"
permalink: /teaching/
---
{% for teaching in site.data.courses-taught %}
- **{{ teaching.course }}** – {{ teaching.role }}, {{ teaching.year }}, {{ teaching.institution }}
{% endfor %}
I have been involved in teaching the following courses.