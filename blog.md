---
layout: default
title: Blog
permalink: /blog/
---
<div class="hero">

<h2>All Posts</h2>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span>({{ post.date | date: "%b %-d, %Y" }})</span>
    </li>
  {% endfor %}
</ul>
</div>