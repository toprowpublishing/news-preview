---
layout: default
title: About
permalink: /about/
---

<h1>Staff</h1>

<ul style="list-style-type: none;">
  {% for author in site.authors %}
    <li>
      <h2>{{ author.name }}</h2>
      <h3>{{ author.position }}</h3>
      <p>{{ author.content | markdownify }}</p>
    </li>
  {% endfor %}
</ul>
