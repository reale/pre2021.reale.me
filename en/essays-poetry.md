---
layout: page
title: Essays and Poetry
lang: en
ref: essays-poetry
permalink: /en/essays-poetry
---

<section>
	<div class="posts">
	{% assign posts = site.categories.poetry | where: "lang", page.lang %}
	{% for post in posts %}
		{% unless post.categories contains 'misc' %}
		<article>
			<a href="{{ site.baseurl }}{{ post.url }}" class="image"><img src="{{ post.image }}" alt="" /></a>
			<h3><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h3>
			<p>{{ post.excerpt }}</p>
			<ul class="actions">
				<li><a href="{{ post.url }}" class="button">{{ site.data.labels.read-more[page.lang] }}</a></li>
			</ul>
		</article>
		{% endunless %}
	{% endfor %}
	</div>
</section>
