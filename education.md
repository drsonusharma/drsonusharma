---
layout: page
title: Education
---
<ul>
  {% for post in site.categories.education %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
