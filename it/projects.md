---
layout: page
title: Progetti
lang: it
ref: projects
permalink: /it/projects
---

<section>
	<header class="major">
		<h2><a id="egov">E-government</a></h2>
	</header>
	<div class="posts">
    {% assign egov = site.categories.egov | where: "lang", page.lang | sort: "order" | reverse %}
	{% for post in egov %}
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

<section>
	<header class="major">
		<h2><a id="blockchain">Blockchain</a></h2>
	</header>
	<div class="posts">
    {% assign blockchain = site.categories.blockchain | where: "lang", page.lang | sort: "order" | reverse %}
	{% for post in blockchain %}
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

<section>
	<header class="major">
		<h2><a id="software">Software</a></h2>
	</header>
	<div class="posts">
    {% assign software = site.categories.software | where: "lang", page.lang | sort: "order" | reverse %}
	{% for post in software %}
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
