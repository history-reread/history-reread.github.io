---
layout: page
title: გადაკითხული ისტორია
permalink: /
---

სტატიები ისტორიის საკითხებზე, რომლებიც არასწორად ან არასრულადაა გაგებული.

## სტატიები

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
