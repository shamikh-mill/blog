---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: page
---

# Home

Hey there! I'm Shamikh Hossain, a computer science and economics student at Duke University. My interests are in data science, economic history and web development. This blog will serve as a "repository" (can't escape them) for my thoughts on programming, economics, and other cool stuff. 

I probably seem all over the place, but basically, I enjoy applying computational and mathematical methods to different kinds of phenomena. This summer, I'll be conducting research on electricity access in developing countries using machine learning techniques (i.e. a convolutional neural network) under Dr. Kyle Bradbury of the [Duke Energy Data Analytics Lab](https://energy.duke.edu/research/energy-data). 


# Recent Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{post.url}}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
