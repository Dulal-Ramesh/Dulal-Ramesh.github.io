---
layout: page
title: "Teaching"
permalink: /teaching/
---

## Courses Taught

{% for teaching in site.data.cv.teaching-experience %}
- **{{ teaching.course }}** – {{ teaching.role }}, {{ teaching.year }}, {{ teaching.institution }}
{% endfor %}

I have been involved in teaching both introductory and advanced economics courses, focusing on student engagement and quantitative analysis.