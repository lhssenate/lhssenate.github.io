---
layout: default
title: LHS Student-Faculty Senate
---

<ul>
{% for page in site.pages reversed %}
  {% if page.layout == 'senators' %}
    <li><a href="{{ page.url }}">{{ page.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>