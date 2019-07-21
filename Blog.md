---
layout: homepage
name: Blog page
permalink: Blog
last_modified_at: "2019-07-21"

---

{% for post in site.posts %}
<div class="article-container">
	<div class="article-image">
		<a href="{{ post.url | relative_url }}"> <img src="#" data-src="{{post.image}}" class="lazy" alt="{{post.title}}" title="{{post.title}}"> </a>
	</div>
	<article>
		<h1><strong>{{post.title}}</strong></h1>
		<p>{{post.description | truncate: 180 }}</p>
		<ul>
			<li><a href="{{post.url | relative_url}}" target="_blank" rel="noopener">{{post.title}}</a></li>
		</ul>
	</article>
</div> 
{% endfor %}