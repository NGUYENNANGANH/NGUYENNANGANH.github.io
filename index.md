---
layout: home
title: "Blog của Nguyễn Năng Anh"
description: "Chào mừng đến với blog cá nhân của tôi!"
---

# Chào mừng đến với Blog của Nguyễn Năng Anh

Đây là blog cá nhân của tôi, nơi tôi chia sẻ những trải nghiệm, kiến thức và những gì tôi học được. Hãy cùng khám phá các bài viết nhé!

## Các bài viết gần đây:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - <small>{{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>
