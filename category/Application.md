---
title: 
category:
order: 2
---

# Application

<ul>
  {% for post in site.docs %}
	{% if post.category == "Application" %}
		<li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
	{% endif %}
  {% endfor %}
</ul>