---
layout: default
title: "My Blog"
---

# Welcome to My Blog

Here are my latest posts:

<ul>
{% for post in site.posts %}
  <li><a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%Y-%m-%d" }}</li>
{% endfor %}
</ul>