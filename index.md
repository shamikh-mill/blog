---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: page
---

I'm Shamikh Hossain, a computer science and economics undergrad at Duke
University. I'm a researcher, web developer, and aspiring machine learning engineer.   


<!-- My research interests are in data science, economic
development, cryptocurrency, and machine-learning, and this site serves to be an
online homebase for my adventures in these fields, and as a repository for my notes, thoughts, projects, etc. 
 -->
I enjoy building models and applying computation to investigate interesting economic problems. This summer, I'll be conducting research on electricity access in developing countries
using deep learning under
Dr. Kyle Bradbury of the
[Duke Energy Data Analytics Lab](https://energy.duke.edu/research/energy-data).


# What I've been up to:  
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a>
    </li>
  {% endfor %}
</ul>


<!-- https://github.com/jekyll/jekyll/issues/332 -->
