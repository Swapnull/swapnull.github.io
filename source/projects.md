---
layout: page
title: Projects
permalink: /projects/
---

<ul id="project-list">
{% for item in site.projects %}
  
  <h1> <a href="{{ item.url }}">{{ item.title }}</a></h1>
  <span class="grid-half">  <img src="{{ item.image | prepend: site.baseurl }}"> </span>
  <span class="grid-half text-center"> <h4> {{ item.tagline }}</h4> <p> {{ item.description }} </p> </span>

{% endfor %}

</ul>
