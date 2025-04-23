---
layout: default
title: Python Posts
---

# Python Articles

{% for post in site.categories.python %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%b %d, %Y" }}
{% endfor %}
