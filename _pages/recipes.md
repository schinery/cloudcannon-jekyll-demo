---
layout: media
permalink: /recipes/
share: false
title: Recipes
---

{% for recipe in site.recipes %}
  <div class="recipe">
    <h2><a href="{{ recipe.url }}">{{ recipe.title }}</a></h2>
  </div>
{% endfor %}