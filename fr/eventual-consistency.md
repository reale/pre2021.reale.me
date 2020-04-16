---
layout: page
title: Eventual Consistency
lang: fr
ref: eventual-consistency
permalink: /fr/eventual-consistency
---

Ce blog est également disponible sur [Medium](https://medium.com/reale).

<section>
	<div class="posts">
	{% assign posts = site.categories.articles | where: "publication", "Eventual Consistency" %}
	{% for post in posts %}
		<article>
			<a href="{{ site.baseurl }}{{ post.url }}" class="image"><img src="{{ post.image }}" alt="" /></a>
			<h3><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h3>
			<p>{{ post.excerpt }}</p>
			<ul class="actions">
				<li><a href="{{ post.url }}" class="button">{{ site.data.labels.read-more[page.lang] }}</a></li>
			</ul>
		</article>
	{% endfor %}
	</div>
</section>
