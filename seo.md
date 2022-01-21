---
layout: page
title: SEO
---
<ul>
  {% for post in site.categories.seo %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
