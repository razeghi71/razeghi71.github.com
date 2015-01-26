---
layout: page
title: پا‌نوشته‌های یک کمپوت اسب
tagline: 
---
<div id="wrapper" dir="rtl">
<div id="page" class="container">
{% for post in site.posts limit 10 %}
<div>
	<h2>{{ post.title }}</h2>
    <div style="font-size:15px;">{{ post.content | strip_html | truncatewords : 60 }}</div>
    <a class="posted-style" href="{{ post.url }}" style="margin-top:15px;">دیدن کامل پست و کامنت </a>
</div>
<br>
<br>
{% endfor %}
</div>
<p id="tsa" style="margin-bottom:20px;"><a href="http://torob.ir" target="_blank"><img 
src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADkAAAA+CAMAAACmw0MPAAAAWlBMVEVMaXHlGDflGDd4oi7lGDflGDd4oi7lGDflGDflGDd4oi7lGDd4oi54oi54oi54oi7lGDflGDd4oi54oi7lGDflGDflGDd4oi7lGDflGDd4oi54oi7lGDd4oi6Hubz4AAAAHHRSTlMA0CCAQIDAEPDAojAQaNBIoLAwkGDgcPCQUCDg/EEITwAAAY9JREFUeNqdltuygjAMRYO0lILcBBA0/P9vHqZQIhwGSNarrtndSe0Ix2Tj+H4CAxInEoH4mjxG6CfJ/Fej0VHcNMMpJfORjvC26buFEnOsASBhmtlaLhoZPaldQuYHbvJ1X/+uZnRPo8HslpIq9bhU88Wsl2MbXbU4Y/vGnJjPZD5tsfTtcYNtzuab5y+Y1CgpAEyMO2JtdlmZa5bX22GW+J92+PXq9+ipgRjwkNKsYu617SbSGI8JvOpEorgQSd2bIYlX6jP6Fd/zkDo8pfKr+FLNF0w8LF7QrZe9jtxWnGc0XhIfXMiHjvEG5dZKlQ7wJhTqLhuDHgiNHGJuJKGYkYSWRqL1ZoNMWm9WyMWbKDVTsdmJTS0xaUCiS2TZphWbWmwqsQkLPb+mdCudNxUSzNcECeYLVrEjZb/PQPzyaZA+fQqkobBh4NaUjNfuTBMwTKHawp40YM6WMJZ7XKKLmaHEo2Tu5dptN6dp4BDTlHZTq9KDWT5SfTyP94RUOSaFoD8vA0hILWIJMprO/AGn6O3uRfZTvAAAAABJRU5ErkJggg==" 
alt=""><span id="tt">تُرُب</span><span class="td">موتور جستجوی هوشمند خرید</span><span class="td ex">ساخته شده  با افتخار در دانشگاه شریف</span></a></p>
</div>
