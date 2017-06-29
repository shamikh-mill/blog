---
layout: page
title: Projects
permalink: /projects/
---

- UAV Animal Tracking - Developing new animal-tracking system using
drones, computer vision libraries and a new lightweight-tagging method

- DAMUN Website - Created new conference [website](http://damunconference.org/) for Model UN school
organization, website was awarded grant from UN Foundation of America

- Video Tutorial Series - maintained YouTube [channel](https://www.youtube.com/user/computerpowerguide) of tutorials on
computer software and graphic design, accumulated 185,000+ video views

- IB Extended Essay in History: [The Effect of Civil Service Examinations on the Great Divergence in Late Dynastic China](http://shamikh-mill.github.io/ee.pdf)


Blog Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{site.baseurl}}{{ post.url }}">{{post.title}}</a>
    </li>
  {% endfor %}
</ul>
