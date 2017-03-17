---
layout: page
title: L'espace
permalink: /espace/
---

Notre super espace attend votre visite.

## Horaires

Nous sommes ouverts officiellement de 9h à 18h du lundi au vendredi.

Nous nous organisons entre coworkers pour gérer les clés, ce qui fait que les horaires s'adaptent à vos besoins.

## Services

{% for service in site.data.services %}

- {{ service.name }}

{% endfor %}

## À proximité

- De quoi manger équilibré ou gras

{% for place in site.data.places %}

- {{ place.name }} <span>{{ place.distance }}</span> <span>{{ place.time }}</span> 

{% endfor %}