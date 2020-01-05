---
layout: page
title: Misc
lang: en
ref: misc
permalink: /en/misc
---

<section>
	<ul>
	{% for post in site.categories.misc %}
		<li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
	</ul>
</section>
