---
title: Programma
permalink: /pages/programma/
---

## Aankomende Programma's en Evenementen

<ul>
{% for e in site.events | sort: 'date' %}
  <li>
    <a href="{{ e.url }}">{{ e.title }}</a> — 
    {% if e.date %}{{ e.date | date: "%d %b %Y" }}{% endif %}
    {% if e.time %} · {{ e.time }}{% endif %}
  </li>
{% endfor %}
</ul>
