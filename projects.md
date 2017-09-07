---
layout: page
title: Projects
permalink: /projects/
---

Projects

Stuff I've worked on, am currently working on, or have contributed to

- Power Plant Dataset - A supervised-learning training dataset of sattelite imagery of powerplants agglomerated in Summer 2017 research program for potential usage in computer vision and machine learning applications or models. Published on Figshare [here](https://figshare.com/articles/Power_Plant_Satellite_Imagery_Dataset/5307364). Used Python/NumPy/SciPy, ArcGIS. 

- Biology IT Inventory - A web platform built using Django, the Django REST Framework and PostgreSQL for keeping track of laoner equipment inventory of the Biology IT helpdesk. 

- Hitchecker - A research tool and Python [program](https://github.com/tn74/MTurkAnnotationTool/blob/master/ASCRIPT_hit_checker.py) that uses the Amazon Mechanical Turk API to allow researchers/Turk users to review image labels and annotations received for their crowdsourced Human Intelligence Tasks (HITs). Built in Summer 2017 research as part of an end-to-end web platform for receiving and reviewing responses on Amazon Mechanical Turk for construcing machine learning training datasets related to imagery. 

- Duke Registration Enhancer (Contributor to open source project) - Duke Registration Enhancer is a chrome extension that provides front-end visual enhancements to Duke University's online class registration platform. I modified a lookup feature that used to make an excess amount of requests to the RateMyProfessors website to pull rating information by implementing a request-free link generation algorithm using JavaScript. 

- DAMUN Website - Created new conference [website](http://damunconference.org/) for Model UN school organization, website was awarded grant from UN Foundation of America

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
