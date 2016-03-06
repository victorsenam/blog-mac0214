---
layout: post
title: Estatísticas
hours: 0
solved: 0
---

{% for post in site.posts %}
    {% assign hours = hours | plus: post.hours %}
    {% assign solved = solved | plus: post.solved %}
{% endfor %}

Seguem algumas estatísticas úteis sobre o meu progresso na matéria. A ideia de inserir estes contadores foi inspirada por (descaradamente copiada de) [Nathan Benedetto Proença](http://github.com/nathanPro) com a permissão do mesmo.

- Horas de Treinos Registradas: **{{ hours }}**
- Problemas Resolvidos em Contest Registrados: **{{ solved }}**
