---
layout: default
title: Home
---

# Knowledge is the real exploit.

Logging what I uncover in the shadows.

## Recent Drops


<ul>
  {% for post in site.posts limit:5 %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%B %d, %Y" }}</li>
  {% endfor %}
</ul>
