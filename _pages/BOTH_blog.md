---
title: Blog
description: Currently writing...
permalink: /both_blog/

layout: featurerow
feature_row:
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> {{ post.description }}
    </li>
  {% endfor %}
</ul>
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> {{ post.description }}
    </li>
  {% endfor %}
</ul>