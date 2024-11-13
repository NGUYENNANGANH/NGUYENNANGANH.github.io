---
layout: page
title: "Cuoc song o que"
permalink: /oque/
---

# Các bài viết về DSA

<ul>
  {% for post in site.posts %}
    {% if post.categories contains "DSA" %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a> - <small>{{ post.date | date: "%B %d, %Y" }}</small>
      </li>
    {% endif %}
  {% endfor %}
</ul>
