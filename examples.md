---
layout: default
title: examples
---

# Examples

{% for ex in site.examples %}
  <h3><a href="{{ ex.id }}">{{ ex.title }}</a></h3>
{% endfor %}