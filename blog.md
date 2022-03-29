---
layout: default
title: "Blog"
---

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include physics.html title="Posts" %}
{% endif %}

