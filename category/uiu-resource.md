---
layout: default
title: UIU Resources
---

# Machine Learning Articles

{% for post in site.categories.uiu-resource %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%b %d, %Y" }}
{% endfor %}
