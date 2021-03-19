---
layout: collection
title: "Methods: Synthetic control"
author_profile: true
header:  
  overlay_color: "#000"
  overlay_image: /assets/images/IMG_1221.JPG
permalink: /synthetic-control/
---

<ul>
  {% for post in site.tags.synthetic-control %}
    {% if post.url %}
       <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
