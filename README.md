---
title: awesome-devs
description: Everytime I come across good Github profiles I index them here
---

# awesome-devs
Everytime I come across good Github profiles I index them here

{% for dev in site.data.devs %}
- {{ dev.github }}
  {{ dev.linkedin }}
{% endfor %}

