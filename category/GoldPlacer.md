---
title: 
category:
order: 3
---

# Gold placer

<ul>
  {% for post in site.docs %}
	{% if post.category == "GoldPlacer" %}
		<li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
	{% endif %}
  {% endfor %}
</ul>
