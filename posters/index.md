---
layout: default
title: Posters
---

In the SCAMs@bristol group, we try our baest to make interesting and descriptive posters to present at research meetings. 
You can see some of these posters below. 

<center>

  {% for post in site.data.posters %}
  <picture>
    <a href="{{ post.path }}">
      <img src="{{ post.path }}" width="100%" alt="{{ post.alt }}">
    </a>
  </picture><br>
</center>
