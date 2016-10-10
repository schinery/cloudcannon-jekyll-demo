---
layout: media
title: List of Things
permalink: /list-of-things
share: false
---

This is the list of things page.

<ul>
{% for thing in site.data.things %}
  <li>{{ thing.title }}</li>
{% endfor %}
</ul>
