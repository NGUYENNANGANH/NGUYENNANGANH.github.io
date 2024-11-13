---
layout: page
title: "Chủ đề Cuộc sống"
permalink: /life/
---

# Các bài viết về Cuộc sống

<ul>
  {% for post in site.posts %}
    {% if post.categories contains "Cuộc sống" %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a> - <small>{{ post.date | date: "%B %d, %Y" }}</small>
      </li>
    {% endif %}
  {% endfor %}
</ul>
