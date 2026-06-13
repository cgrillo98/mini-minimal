---
layout: default
title: Inicio
---

# Bienvenido

Este sitio sigue principios de Minimal Computing:

- HTML semántico
- Sin frameworks pesados
- Sin JavaScript innecesario
- Accesibilidad primero
- Bajo consumo de ancho de banda

## Entradas recientes

{% raw %}
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}
{% endraw %}
