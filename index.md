---
layout: page
title: გადაკითხული ისტორია
permalink: /
---

სტატიები ისტორიის იმ საკითხებზე, რომლებიც ხშირად არასწორად ან არასრულად არის გაგებული.

## სტატიები

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
