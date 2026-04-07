---
title: Home
---

# History Re-read

Essays on historical questions that are often misunderstood or only partially understood today.

## Articles

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
