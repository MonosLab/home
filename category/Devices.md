---
title: 
category:
order: 1
---

# Devices

<ul>
  {% for post in site.docs %}
	{% if post.category == "Devices" %}
		<li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
	{% endif %}
  {% endfor %}
</ul>