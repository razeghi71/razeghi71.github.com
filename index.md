---
layout: page
title: 	
tagline: 
---
<div id="wrapper" dir="rtl">
<div id="page" class="container">
{% for post in site.posts limit 10 %}
<div>
	<h2>{{ post.title }}</h2>
    <div style="font-size:15px;">{{ post.content | strip_html | truncatewords : 50 }}</div>
    <a class="posted-style" href="{{ post.url }}">دیدن کامل پست و کامنت </a>
</div>
<br>
<br>
{% endfor %}
</div>
</div>