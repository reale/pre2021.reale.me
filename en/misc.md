---
layout: page
title: Misc
lang: en
ref: misc
permalink: /en/misc
---

<section>
	<header class="major">
		<h2><a id="misc">Misc</a></h2>
	</header>
	<ul>
	{% for post in site.categories.misc %}
		<li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
	</ul>
</section>
