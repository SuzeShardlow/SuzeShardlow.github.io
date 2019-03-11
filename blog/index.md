---
layout: blog_list
headline: Latest Posts
sub_headline: The latest posts from my blog
title: "Suze Shardlow :: Blog"
main_image: typewriter3.jpg
---

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2><h4>{{ post.date | date: "%A %-d %B, %Y" }} • {{ post.read_time }} read</h4>

      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
