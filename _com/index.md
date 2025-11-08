---
layout: page
title: "COM 411 — Series Index"
permalink: /com/
---
{% assign parts = site.com | sort: "order" %}
<ol>
{% for p in parts %}
  <li><a href="{{ p.url }}">{{ p.title }}</a> — {{ p.description }}</li>
{% endfor %}
</ol>
