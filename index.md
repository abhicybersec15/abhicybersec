---
layout: default
title: My Cybersecurity Portfolio
---

# Welcome to My Cybersecurity Portfolio

A simple portfolio to showcase my LinkedIn articles and projects in cybersecurity and infrastructure.

## Featured Articles

<ul>
{% for article in site.articles %}
  <li><a href="{{ site.baseurl }}{{ article.url }}">{{ article.title }}</a></li>
{% endfor %}
</ul>
