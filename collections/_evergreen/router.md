---
layout: evergreen
title: Router Operating Systems
mathjax: false
description: |
  Below are a few alternative router operating systems, that can be used on routers, wifi access points etc.
---

{% for item_hash in site.data.operating-systems.router %}
{% assign item = item_hash[1] %}

{% if item.type == "Recommendation" %}
{% include recommendation-card.html %}
{% endif %}

{% endfor %}

