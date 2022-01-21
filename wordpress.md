---
layout: page
title: WordPress
---
<ul>
  {% for post in site.categories.wordpress %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
