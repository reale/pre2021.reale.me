---
layout: page
title: Book Reviews
lang: it
ref: misc
permalink: /it/book-reviews
---

<section>
	<ul>
	{% for post in site.categories.book-reviews %}
		<li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
	</ul>
</section>
