---
layout: default
title: "About me"
---

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="About me" %}
{% endif %}