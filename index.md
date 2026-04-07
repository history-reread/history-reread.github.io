---
layout: page
title: გადაკითხული ისტორია
permalink: /
---

სტატიები ენისა და ისტორიის საკითხებზე.

## სტატიები

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
