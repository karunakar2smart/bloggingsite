---
layout: homepage
name: Blog page
permalink: Blog

---

{% for post in site.posts %}
<div class="article-container">
	<div class="article-image">
		<a href="{{ post.url | relative_url }}"> <img src="#" data-src="{{post.image}}" class="lazy" alt="free-online-typing-jobs" title="Free-online-typing-jobs"> </a>
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