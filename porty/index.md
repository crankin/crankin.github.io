---
layout: default
title: porty
categories: porty
---

<div id="home">
    <h2>porty</h2>
      <ul class="posts">
    {% for post in site.categories.porty %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
</div>