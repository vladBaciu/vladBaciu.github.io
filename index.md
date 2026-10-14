---
layout: default
title: Home
---

# Welcome to My Blog

Hello! I'm **Vlad Baciu**, a developer passionate about **Embedded Systems**, **Machine Learning**, and **Security**.

I focus on applying machine learning to wearable sensors and edge computing, particularly in **Photoplethysmography (PPG)** for non-invasive health monitoring.

## 📌 Quick Links

- **[Blog Posts](/blog)** - Read my latest articles
- **[Featured Projects](/projects)** - Explore my repositories
- **[About Me](/about)** - Learn more about me

---

## 🔥 Latest Posts

<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span class="date">{{ post.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>

[View all posts →](/blog)