---
layout: default
title: Jisan's ThinkLab
---

## 👋 Welcome to My ThinkLab!
Data Science undergrad | Pythonista | Explorer of data & ideas

---

## 📌 Featured Posts
{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url }}) ({{ post.date | date: "%b %d, %Y" }})
{% endfor %}

[View all posts](/archive)

---

## 🔗 Connect
📘 [Facebook]({{ site.facebook_url }})  
📧 [Email](mailto:{{ site.email }})

---

## 🗂️ Categories
- [🧠 Machine Learning](/category/ml)
- [🐍 Python](/category/python)
- [🚀 Islam](/category/islam)
- [📚 UIU Resources](/category/uiu-resource)
