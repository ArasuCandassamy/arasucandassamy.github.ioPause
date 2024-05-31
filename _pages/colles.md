---
layout: categories
title: "Colles"
permalink: /colles/
---


Bienvenue sur la page dédiée aux sujets de colles avec quelques éléments de correction.

## Liste des Colles 2023-2024

### Sujet de colle 28 : Série numérique
<a href="../sdc/S28.pdf" class="btn btn-enonce" role="button" target="_blank">Énoncé</a>

### Sujet de colle 27 : Probabilité sur un univers fini & Variable aléatoire réel
<a href="../sdc/S27.pdf" class="btn btn-enonce" role="button" target="_blank">Énoncé</a>

### Sujet de colle 26 : Déterminant & Probabilité sur un univers fini
<a href="../sdc/S26.pdf" class="btn btn-enonce" role="button" target="_blank">Énoncé</a>

### Sujet de colle 25 : EPR - Groupe Symétrique & Déterminant
<a href="../sdc/S25.pdf" class="btn btn-enonce" role="button" target="_blank">Énoncé</a>

### Sujet de colle 24 : Espace Préhilbertien Réel
<a href="../sdc/S24.pdf" class="btn btn-enonce" role="button" target="_blank">Énoncé</a>

### Sujet de colle 23 : Intégration et Calcul Intégrale
<a href="../sdc/S23.pdf" class="btn btn-enonce" role="button" target="_blank">Énoncé</a>

### Sujet de colle 22 : Intégration
<a href="../sdc/S22.pdf" class="btn btn-enonce" role="button" target="_blank">Énoncé</a>

{% assign pdfs = site.static_files | where: "path", "sdc" %}
{% for pdf in pdfs %}
  - [{{ pdf.basename | capitalize }}]({{ pdf.path }})
{% endfor %}