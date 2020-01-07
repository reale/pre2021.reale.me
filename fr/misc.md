---
layout: page
title: Misc
lang: fr
ref: misc
permalink: /fr/misc
---

<section>
	<ul>
	{% for post in site.categories.misc %}
		<li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
	</ul>
</section>
