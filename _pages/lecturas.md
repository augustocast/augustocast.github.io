---
layout: page
title: Reseñas
permalink: /lecturas/
---

<div class="catalogue">
  {% comment %} Itera sobre todos los posts y filtra por el tag 'lecturas' {% endcomment %}
  {% assign filtered_posts = site.posts | where_exp:"post", "post.tags contains 'Lecturas'" %}

  {% if filtered_posts.size > 0 %}
    {% for post in filtered_posts %}
      {% include catalogue_item.html %} {# Asume que tienes un include llamado catalogue_item.html para mostrar cada post #}
    {% endfor %}
  {% else %}
    <p>Aún no hay lecturas marcadas. ¡Pronto habrá más!</p>
  {% endif %}
</div>