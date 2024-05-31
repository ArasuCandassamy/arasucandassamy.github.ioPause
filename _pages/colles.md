---
layout: default
title: "Colles"
permalink: /colles/
---

# Sujets de Colles et Corrections

Bienvenue sur la page dédiée aux sujets de colles et leurs corrections.

## Liste des Colles

{% assign pdfs = site.static_files | where: "path", "/sdc/" %}
{% for pdf in pdfs %}
  - [{{ pdf.basename | capitalize }}]({{ pdf.path }})
{% endfor %}