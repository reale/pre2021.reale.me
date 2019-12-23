---
layout: default
---

<!-- Section -->
<section>
	<header class="major">
		<h2>Featured Projects</h2>
	</header>
	<div class="features">
	{% for post in site.categories.focusprojects limit:4 %}
		<article>
			<span class="icon {{ post.icon }}"></span>
			<div class="content">
				<h3><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h3>
				<p>{{ post.excerpt }}</p>
			</div>
		</article>
	{% endfor %}
	</div>
</section>

<!-- Section -->
<section>
	<header class="major">
		<h2>News</h2>
	</header>
	<div class="posts">
	{% for post in site.posts limit:12 %}
		{% unless post.hidden_from_news == true %}
		<article>
			<a href="{{ site.baseurl }}{{ post.url }}" class="image"><img src="{{ post.image }}" alt="" /></a>
			<h3><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h3>
			<p>{{ post.excerpt }}</p>
			<ul class="actions">
				<li><a href="{{ site.baseurl }}{{ post.url }}" class="button">More</a></li>
			</ul>
		</article>
		{% endunless %}
	{% endfor %}
	</div>
</section>
