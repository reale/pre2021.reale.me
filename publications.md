---
layout: page
---

<section>
	<header class="major">
		<h2><a id="articles">Articles</a></h2>
	</header>
	<div class="posts">
	{% for post in site.categories.articles %}
		<article>
			<a href="{{ site.baseurl }}{{ post.url }}" class="image"><img src="{{ post.image }}" alt="" /></a>
			<h3><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h3>
			<p>{{ post.excerpt }}</p>
			<ul class="actions">
				<li><a href="{{ post.url }}" class="button">More</a></li>
			</ul>
		</article>
	{% endfor %}
	</div>
</section>

<section>
	<header class="major">
		<h2><a id="poetry">Poetry</a></h2>
	</header>
	<div class="posts">
	{% for post in site.categories.poetry %}
		<article>
			<a href="{{ site.baseurl }}{{ post.url }}" class="image"><img src="{{ post.image }}" alt="" /></a>
			<h3><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h3>
			<p>{{ post.excerpt }}</p>
			<ul class="actions">
				<li><a href="{{ post.url }}" class="button">More</a></li>
			</ul>
		</article>
	{% endfor %}
	</div>
</section>
