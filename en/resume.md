---
layout: page
title: Resume
lang: en
ref: resume
permalink: /en/resume
---

<section>
	<header class="major">
		<h2><a id="experience">Experience</a></h2>
	</header>
	<div class="posts">
	{% for post in site.categories.experience %}
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
		<h2><a id="teaching">Teaching</a></h2>
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
