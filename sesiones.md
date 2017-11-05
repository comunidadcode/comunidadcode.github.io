---
layout: page
title: Sesiones pasadas
subtitle: Sesiones organizadas hasta ahora por CODE
---

{% for post in site.posts %}
  * {{ post.date | date: "%d/%m/%Y" }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}
