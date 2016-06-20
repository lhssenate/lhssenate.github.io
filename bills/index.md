---
layout: default
title: LHS Student-Faculty Senate
---

<ul>
{% for page in site.pages reversed %}
  {% if page.layout == 'bill' %}
    <li><a href="{{ page.url }}">{{ page.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>

<a href="unconverted.txt">Bills not yet converted to the new website format</a>
