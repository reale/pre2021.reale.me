---
layout: page
permalink: /datalab/wordcloud/
---

<section>
	<header class="major">
		<h2><a id="wordcloud">Wordcloud</a></h2>
	</header>
	<div class="posts">
	{% for post in site.categories.wordcloud %}
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