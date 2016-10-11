---
layout: media
permalink: /things/
share: false
title: Things
---

This is the list of things page.

<ul>
{% for thing in site.data.things %}
  <li>{{ thing.title }}</li>
{% endfor %}
</ul>
