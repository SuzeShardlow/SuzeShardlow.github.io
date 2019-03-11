---
layout: default
headline: Latest Posts
title: Blog
---

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2><h4>{{ post.date | date: "%A %-d %B, %Y" }} • {{ post.read-time }} read</h4>

      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
