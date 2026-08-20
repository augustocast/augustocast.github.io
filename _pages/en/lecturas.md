---
layout: page
title: Reads
lang: en
permalink: /en/reads/
translation_url: /lecturas/
---

{% assign filtered_posts = site.posts | where_exp:"post", "post.tags contains 'Lecturas'" | where: "lang", "en" %}

<div class="catalogue">
  {% if filtered_posts.size > 0 %}
    {% for post in filtered_posts %}
      {% include catalogue_item.html %}
    {% endfor %}
  {% else %}
    <p class="home-empty">{{ site.data.i18n.en.reads.empty }}</p>
  {% endif %}
</div>
