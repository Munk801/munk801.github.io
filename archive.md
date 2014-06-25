---
layout: page
title: Archive
---

## Posts
<ul>
	{% for post in site.posts %}
		<li>
			<a href="{{ post.url }}">{{ post.title }} - {{ post.date | date_to_string}}</a>
					  {{ post.excerpt }}
		</li>
	{% endfor %}
</ul>

