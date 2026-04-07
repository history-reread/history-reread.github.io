---
title: History Re-read
---

# გადაკითხული ისტორია

სტატიები ისტორიის საკითხებზე, რომლებიც არასწორად ან არასრულად არის გაგებული.

## სტატიები

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
