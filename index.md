
<html lang="en">
<head>
<title>Marten Waite</title>
</head>


<body>
<h1>
Marten Waite
</h1>
<ul style="
    list-style: none;
    padding-left: 0px;
">
{% for post in site.posts %}
	    <li><a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></li>
	  {% endfor %}
</ul>
	
<p>Contact Waite at martenwaite@protonmail.ch</p>

</body>
</html>
