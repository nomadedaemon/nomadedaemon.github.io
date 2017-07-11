---
layout: default
title: Kategorie
language: de
handle: /category
---
{% for page in site.pages %}
  {% if page.categories contains 'Bio' %}
    <div class="item">
      <h3>{{page.title}}</h3>
      <p>{{page.description}}</p>  
    </div>
  {% endif %}
{% endfor %}
