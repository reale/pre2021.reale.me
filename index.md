---
layout: default
---

<!-- Section -->
<section>
	<header class="major">
		<h2>Erat lacinia</h2>
	</header>
	<div class="features">
		<article>
			<span class="icon fa-diamond"></span>
			<div class="content">
				<h3>Portitor ullamcorper</h3>
				<p>Aenean ornare velit lacus, ac varius enim lorem ullamcorper dolore. Proin aliquam facilisis ante interdum. Sed nulla amet lorem feugiat tempus aliquam.</p>
			</div>
		</article>
		<article>
			<span class="icon fa-paper-plane"></span>
			<div class="content">
				<h3>Sapien veroeros</h3>
				<p>Aenean ornare velit lacus, ac varius enim lorem ullamcorper dolore. Proin aliquam facilisis ante interdum. Sed nulla amet lorem feugiat tempus aliquam.</p>
			</div>
		</article>
		<article>
			<span class="icon fa-rocket"></span>
			<div class="content">
				<h3>Quam lorem ipsum</h3>
				<p>Aenean ornare velit lacus, ac varius enim lorem ullamcorper dolore. Proin aliquam facilisis ante interdum. Sed nulla amet lorem feugiat tempus aliquam.</p>
			</div>
		</article>
		<article>
			<span class="icon fa-signal"></span>
			<div class="content">
				<h3>Sed magna finibus</h3>
				<p>Aenean ornare velit lacus, ac varius enim lorem ullamcorper dolore. Proin aliquam facilisis ante interdum. Sed nulla amet lorem feugiat tempus aliquam.</p>
			</div>
		</article>
	</div>
</section>

<!-- Section -->
<section>
	<header class="major">
		<h2>News</h2>
	</header>
	<div class="posts">
	{% for post in site.posts %}
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
