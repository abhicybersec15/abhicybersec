---
layout: default
title: Home
---

# Welcome

## Articles

<ul>
{% for post in site.posts %}
  <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
---

Thanks for visiting — feel free to explore and reach out if you have questions!
