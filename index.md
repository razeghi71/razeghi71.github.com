---
layout: page
title: پانوشته‌های یک کمپوت اسب
tagline: 
---

<ul >
    {% for post in site.posts limit 10 %}
    <li><a href="{{ BASE_PATH }}{{ post.url }}" style="font-size:20;">{{ post.title }}</a></li>
        {{ post.content | strip_html | truncatewords:75}}<br><br>
            <a href="{{ post.url }}">مطلب کامل</a><br>
	<hr>
    {% endfor %}
</ul>
