---
layout: default
title: My Cybersecurity Portfolio
---

# Welcome to My Cybersecurity Portfolio

A simple portfolio to showcase my LinkedIn articles and projects in cybersecurity and infrastructure.

## Featured Articles

<ul>
{% for page in site.pages %}
  {% if page.path contains 'articles/' %}
    <li><a href="{{ page.url }}">{{ page.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>
