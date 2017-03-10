---
layout: page
title: Projects
permalink: /projects/
---


Blog Posts 
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{post.url}}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
