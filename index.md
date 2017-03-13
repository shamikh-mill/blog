---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: page
---

I'm Shamikh Hossain, a computer science and economics undergrad at Duke University- welcome to my blog! My interests are in data science, economic development, and machine-learning, and this site serves to be an online homebase for my adventures in these fields.

This summer, I'll be conducting research on electricity access in developing countries using machine learning techniques (i.e. a convolutional neural network) under Dr. Kyle Bradbury of the [Duke Energy Data Analytics Lab](https://energy.duke.edu/research/energy-data).


# Recent Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{post.url}}">{{post.title}}</a>
    </li>
  {% endfor %}
</ul>
