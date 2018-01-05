---
layout: page
title: Todas las sesiones
twitter-description: Índice de todas las sesiones que se han llevado a cabo por el momento.
---

{% for post in site.posts %}
  * {{ post.date | date: "%d/%m/%Y" }} &raquo; [ {{ post.title }} ]({{ post.url }}) ([{{ post.speakerName }}](/colaboradores/{{ post.speakerId }}))
{% endfor %}
