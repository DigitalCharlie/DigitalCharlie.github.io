---
layout: page
title: Blog
---

Just a small sampling of thoughts that felt like they merit writing.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>