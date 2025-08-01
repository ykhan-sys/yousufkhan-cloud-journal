---
title: AWS
layout: page
permalink: /aws/
---

# AWS: All Posts

Below is a list of all posts related to AWS:

<ul>
  {% assign aws_posts = site.posts | where_exp: "post", "post.categories contains 'AWS' or post.categories contains 'aws'" %}
  {% for post in aws_posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>{{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>
