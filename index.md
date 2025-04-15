---
layout: default
title: Home
---

<div class="hero">
  <h2>Welcome to InsideOut Blog</h2>
  <p>This is a space where thoughts unravel and the inner world finds expression. Slow down, breathe deep, and explore ideas that live beneath the surface.</p>
</div>

<!-- Blog posts list below -->
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span>({{ post.date | date: "%b %-d, %Y" }})</span>
    </li>
  {% endfor %}
</ul>
