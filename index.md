---
layout: page
title: 
tagline: 
---
{% include JB/setup %}

<ul class="posts">
  {% for post in site.posts %}
    <li> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

