---
layout: single
title: "Academic Service"
permalink: /service/
author_profile: true
---

{% include base_path %}

## Program Committee

{% assign pc_items = site.service | where: "type", "Program Committee" %}
<ul>
{% for item in pc_items %}
  <li>{{ item.venue }}, {{ item.year }}</li>
{% endfor %}
</ul>
