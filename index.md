---
layout: default
title: "Home"
---

{% if site.show_excerpts %}
  {% include home.md %}
{% else %}
  {% include archive.md title="Posts" %}
{% endif %}
