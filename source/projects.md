---
layout: page
title: Projects
permalink: /projects/
---

<ul>
{% for item in site.projects %}
  
  <h1> <a href="{{ item.url }}">{{ item.title }}</a></h1>
  <h4> {{ item.description }}</h4>
  <img src="{{ item.image | prepend: site.baseurl }}">
{% endfor %}

</ul>
