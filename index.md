---
layout: page
title: پانوشته‌های یک کمپوت اسب
tagline: 
---

<ul >
    {% for post in site.posts limit 10 %}
    <li><a href="{{ BASE_PATH }}{{ post.url }}" style="font-size:20px;">{{ post.title }}</a> <br> <br>
        <div style="font-size:15px;">{{ post.content | strip_html }}</div>
        <a  style="font-size:12px;" href="{{ post.url }}">کامنت بگذارید ... </a><br>
		<hr>
	</li>
    {% endfor %}
</ul>
