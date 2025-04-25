---
layout: default
title: Home
---

# Welcome to My Blog

이곳은 심플한 Jekyll 블로그입니다.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%Y-%m-%d" }}
    </li>
  {% endfor %}
</ul>
