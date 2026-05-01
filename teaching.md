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
<span class="teaching-syllabus-link"><i class="fa-solid fa-file-pdf" aria-hidden="true"></i> <a href="{{ teaching.syllabus | relative_url }}" target="_blank" rel="noopener">Please find the syllabus here</a></span>
  {% endif %}
{% endfor %}
