---
layout: page
title: Paginas Web Mexicali Mexico | Julio Cesar Montenegro
permalink: /
description: Necesitas una pagina web para darte a conocer, por favor contactame a (686) 210 2600
group: "navigation"
---

#Diseño y Desarrollo Web en Mexicali, Mexico

Mi nombre es Julio Cesar Montenegro, también conocido como huleos. Soy especialista en diseño y desarrollo web de tiempo completo desde 2007, trabajo con tecnologías HTML, CSS y JS. Tengo experiencia trabajando con Ruby on Rails, Python/Django, Jekyll, WordPress y PHP en general.

<div class="row">
  {% for post in site.posts %}
    <div class="col md-4">
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
      {{ post.excerpt }}
    </div>
  {% endfor %}
</div>