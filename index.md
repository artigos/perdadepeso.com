---
layout: index
title: Perda de Peso
overview: true
---

Seguir uma dieta para tratar o problema de obesidade é difícil, exige esforço e sacrifício e requer tempo. Por isso os que sofrem de peso em excesso sentem-se atraídos e seduzidos por dietas novas prometendo um êxito rápido e isento de sacrifícios.

Não obstante, algumas destas dietas são desequilibradas e, continuando-se por período prolongado de tempo, podem trazer graves prejuízos à saúde.

<span class="latest-article">Últimos artigos sobre a perda de peso</span>
<ul class="index">
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> <span class="date">{{ post.date | date: "%-d/%m/%Y" }}</span></li>
  {% endfor %}
</ul>