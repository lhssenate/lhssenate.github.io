---
layout: default
title: LHS Student-Faculty Senate
---

Many years are missing due to bad recordkeeping before the move to this new website.

<ul>
{% for page in site.pages reversed %}
  {% if page.layout == 'senators' %}
    <li><a href="{{ page.url }}">{{ page.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>
