---
layout: page
title: پانوشته‌های یک کمپوت اسب
tagline: 
---

<ul >
    {% for post in site.posts limit 10 %}
    <li><a href="{{ BASE_PATH }}{{ post.url }}" style="font-size:20px;">{{ post.title }}</a></li>
        {{ post.content | strip_html }}<br>
            <a href="{{ post.url }}">کامنت بگذارید ... </a><br>
	<hr>
    {% endfor %}
</ul>
