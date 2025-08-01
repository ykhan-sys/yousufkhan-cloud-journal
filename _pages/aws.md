---
title: AWS
layout: page
permalink: /aws/
---

# AWS Posts

<ul>
  {% for post in site.posts %}
    {% if post.categories contains "aws" or post.categories contains "AWS" %}
      <li><a href="{{ post.url }}">{{ post.title }}</a> <small>{{ post.date | date: "%Y-%m-%d" }}</small></li>
    {% endif %}
  {% endfor %}
</ul>
