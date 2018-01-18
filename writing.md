---
layout: page
title: My Writing
---

<p>Sometimes writing helps me process my thoughts.</p>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>