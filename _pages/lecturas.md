---
layout: page
title: Reseñas
permalink: /lecturas/
translation_url: /en/reads/
---

{% assign filtered_posts = site.posts | where_exp:"post", "post.tags contains 'Lecturas'" | where: "lang", "es" %}

<div class="catalogue">
  {% if filtered_posts.size > 0 %}
    {% for post in filtered_posts %}
      {% include catalogue_item.html %}
    {% endfor %}
  {% else %}
    <p class="home-empty">{{ site.data.i18n.es.reads.empty }}</p>
  {% endif %}
</div>