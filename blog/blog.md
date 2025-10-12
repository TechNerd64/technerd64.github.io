---
layout: page
title: "Blog"
permalink: /blog/
---

Hello everyone!  This is a test to make sure I'm using Github pages properly.

# My Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
