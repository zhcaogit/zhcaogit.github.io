---
layout: default
title: "Physics"
---

{% for post in site.posts %}
  {% if post.categories contains 'physics' %}

[{{ post.title }}]({{ post.url }})

  {% endif %}
{% endfor %}
