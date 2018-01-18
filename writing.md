---
layout: page
title: My Writing
---

<p>Sometimes writing helps me process my thoughts.</p>

<ul class="post_list">
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}" class="post_link">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>