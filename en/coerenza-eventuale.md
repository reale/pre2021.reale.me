---
layout: page
title: Coerenza eventuale
lang: en
ref: coerenza-eventuale
permalink: /en/coerenza-eventuale
---

This blog is available also on [Medium](https://medium.com/coerenza).

<section>
	<div class="posts">
	{% assign posts = site.categories.articles | where: "publication", "Coerenza eventuale" %}
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
