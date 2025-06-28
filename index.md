---
layout: default
title: Home
---

# Welcome

## Articles

<ul>
{% for page in site.pages %}
  {% unless page.path contains "_config.yml" or page.path contains "README.md" or page.path contains "LICENSE" or page.path contains "_layouts" or page.path contains "_includes" or page.path contains ".github" %}
    {% if page.title and page.url != "/" %}
      <li><a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></li>
    {% endif %}
  {% endunless %}
{% endfor %}
</ul>
