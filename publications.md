---
layout: page
lang: en
---

<section>
	<header class="major">
		<h2><a id="articles">Articles</a></h2>
	</header>
	<div class="posts">
	{% for post in site.categories.articles %}
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
