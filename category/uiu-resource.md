---
layout: default
title: 📚 UIU Resources
---

## 📚 UIU Resources

Posts related to UIU (course notes, tips, resources, etc):

{% for post in site.categories['uiu-resource'] %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
