---
layout: default
title: "Colles"
permalink: /colles/
---

# Sujets de Colles et Corrections

Bienvenue sur la page dédiée aux sujets de colles et leurs corrections.

## Liste des Colles

{% for post in site.posts %}
  {% if post.categories contains "colles" %}
    - [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%d %B %Y" }}
  {% endif %}
{% endfor %}
