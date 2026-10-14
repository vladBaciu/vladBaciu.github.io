---
layout: default
title: Blog
permalink: /blog
---

# Blog Posts

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
      <p class="date">📅 Published on {{ post.date | date: "%B %d, %Y" }}</p>
      <p>{{ post.excerpt | strip_html | truncatewords: 30 }}</p>
      <a href="{{ post.url }}" class="read-more">Read more →</a>
    </li>
  {% endfor %}
</ul>