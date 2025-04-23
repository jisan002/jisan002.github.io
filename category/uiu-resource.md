---
layout: default
title: UIU Resources
---

# Blessings For UIU students.

{% for post in site.categories.uiu-resource %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%b %d, %Y" }}
{% endfor %}
