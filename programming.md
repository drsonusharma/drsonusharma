---
layout: page
title: Programming
---
<ul>
  {% for post in site.categories.programming %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
