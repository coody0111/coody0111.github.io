---
layout: page
title: Posts
permalink: /posts/
---

# Blog Posts

{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}
