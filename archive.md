---
layout: page
title: არქივი
permalink: /archive/
---

{% assign posts_by_year = site.posts | group_by_exp: "post", "post.date | date: '%Y'" %}

{% for year in posts_by_year %}
  <h2>{{ year.name }}</h2>
  <ul>
    {% for post in year.items %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        — {{ post.date | date: "%m-%d" }}
      </li>
    {% endfor %}
  </ul>
{% endfor %}
