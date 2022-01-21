---
layout: page
title: Howto
---
<ul>
  {% for post in site.categories.howto %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
