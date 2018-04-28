---
layout: examples
title: examples
---

{% assign sortedExs = site.examples | sort: 'index' %}

# Examples

{% for ex in sortedExs %}
  <h3><a href="{{ ex.id }}">{{ ex.title }}</a></h3>
{% endfor %}