---
layout: page
title: Random Writings
lang: en
ref: misc
permalink: /en/random-writings
---

<section>
	<ul>
	{% for post in site.categories.misc %}
		<li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
	</ul>
</section>
