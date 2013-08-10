---
layout: page
title: پانوشته‌های یک کمپوت اسب
tagline: 
---

<html>
<head>
<title>حوری</title>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
<link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body bgcolor="#9f9f9f" dir="rtl"> 
<br>
<table align="center"  cellpadding="0" cellspacing="0">
	<tr bgcolor="#9F9F9F">
		<td valign="top" width="97px">
			<div class='stat'>سلام</div>			
		</td>	
		<td valign="top">
			<img src="images/logo.gif" width="131" height="109">
		</td>
		<td valign="top" width="10px">
			<div class='logout'>خوش اومدین.</div>
		</td>				
	</tr>	
	<tr>
		<td colspan="3" height="33" width="324">
			<img src="images/top.gif" alt="" width="324" height="33" >
		</td>	
	</tr>
	<tr>
		<td bgcolor="#FFFFFF" colspan="3" height="70">
		</td>	
	</tr>
			
	<ul >
	    {% for post in site.posts limit 10 %}
	    <li><a href="{{ BASE_PATH }}{{ post.url }}" style="font-size:20px;">{{ post.title }}</a></li>
		{{ post.content | strip_html | truncatewords:75}}<br>
		    <a href="{{ post.url }}">مطلب کامل</a><br>
		<hr>
	    {% endfor %}
	</ul>



	<tr>
		<td bgcolor="#FFFFFF" colspan="3" height="70">
		</td>	
	</tr>	
	<tr>
		<td align="center" colspan="3">
			<img src="images/bottom.gif"  width="324" height="14">
		</td>			
	</tr>
	<tr>
	</tr>
	<tr>
	<td align="center" colspan="3">
			<img src="images/zir.gif" width="324" height="20">
		</td>			
	</tr>
		
</table>
</body>
</html>
