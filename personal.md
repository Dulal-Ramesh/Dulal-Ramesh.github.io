---
layout: page
title: Personal
permalink: /personal/
---

## Conferences Attended & Presentations

<ul>
{% assign confs = site.data.research.conferences | sort: "date" | reverse %}
{% for c in confs %}
  <li>
    <strong>{{ c.date | date: "%b %Y" }}</strong> —
    <em>{{ c.title }}</em>{% if c.name %} — {{ c.name }}{% endif %}
    {% if c.location %}, {{ c.location }}{% endif %}
    {% if c.link %} [<a href="{{ c.link }}" target="_blank" rel="noopener">program</a>]{% endif %}
    {% if c.slides %} [<a href="{{ c.slides }}">slides</a>]{% endif %}
  </li>
{% endfor %}
</ul>
