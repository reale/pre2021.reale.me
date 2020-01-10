---
layout: page
title: CV
lang: it
ref: resume
permalink: /it/resume
---

<section>
	<header class="major">
		<h2><a id="experience">Incarichi</a></h2>
	</header>
	<div class="posts">
    {% assign experiences = site.categories.experience | where: "lang", page.lang | where_exp: "page", "page.order != nil" | sort: "order" | reverse %}
	{% for post in experiences %}
		<article>
			<h3>{{ post.title }}</h3>
			<p>{{ post.employer }} ({{ post.period }})</p>
			<p>{{ post.excerpt }}</p>
		</article>
	{% endfor %}
	</div>
</section>

<section>
	<header class="major">
		<h2><a id="teaching">Insegnamento</a></h2>
	</header>
	<div class="posts">
	{% for post in site.categories.teaching %}
		<article>
			<h3>{{ post.title }}</h3>
			<p>{{ post.employer }} ({{ post.period }})</p>
			<p>{{ post.excerpt }}</p>
		</article>
	{% endfor %}
	</div>
</section>
