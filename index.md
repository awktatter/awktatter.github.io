---
layout: default
title: Home
---

## About Me

Welcome to my site! This is where I share my thoughts and articles.

## Brewed Articles

<ul>
  {% for post in site.brewed %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>
