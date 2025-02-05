---
layout: page
title: "Courses Taught"
permalink: /teaching/
---
I have been involved in teaching the following courses.
{% for teaching in site.data.courses-taught %}
- **{{ teaching.course }}** – {{ teaching.role }}, {{ teaching.year }}, {{ teaching.institution }}
{% if teaching.syllabus %}
<br>
<span style="margin-top: -20px; display: block;">📄 <a href="{{ teaching.syllabus }}" target="_blank">Please find the Syllabus here</a></span>
  {% endif %}
{% endfor %}
