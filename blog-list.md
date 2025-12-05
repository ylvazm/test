---
layout: default
title: Blog
---

# Blog

View all blog posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>({{ post.date | date: "%d.%m.%Y" }})</small>
    </li>
  {% endfor %}
</ul>
