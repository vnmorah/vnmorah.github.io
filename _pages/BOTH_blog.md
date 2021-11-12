---
title: Blog
description: Currently writing...
permalink: /both_blog/

---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> {{ post.description }}
    </li>
  {% endfor %}
</ul>