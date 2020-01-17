---
layout:  post
title:  categories
permalink: category.html
image: /
datepublished: "2019-08-30"
datemodified: "2019-08-30"
---

{% assign rawcats = "" %}
{% for post in site.posts %}
{% assign tcats = post.categories | join:'|' | append:'|' %}
{% assign rawcats = rawcats | append:tcats %}
{% endfor %}

{% assign rawcats = rawcats | split:'|' | sort %}

{% assign cats = "" %}

{% for cat in rawcats %}
{% if cat != "" %}

{% if cats == "" %}
{% assign cats = cat | split:'|' %}
{% endif %}

{% unless cats contains cat %}
{% assign cats = cats | join:'|' | append:'|' | append:cat | split:'|' %}
{% endunless %}
{% endif %}
{% endfor %}

<h1 class="page-title">
  <a href="/blog">Blog</a> | {{ page.title }}
</h1>
<br/>

<div class="posts">
<p>
{% for ct in cats %}
<a href="#{{ ct | slugify }}" class="codinfox-categories-mark" style="color:#999;text-decoration: none;"> {{ ct }} </a> &nbsp;&nbsp;
{% endfor %}
<a href="#no-categories" class="codinfox-categories-mark" style="color:#999;text-decoration: none;"> No categories </a> &nbsp;&nbsp;
</p>

{% for ct in cats %}
<h2 id="{{ ct | slugify }}">{{ ct }}</h2>
<ul class="codinfox-categories-list">
  {% for post in site.posts %}
  {% if post.categories contains ct %}
  <li>
    <h3>
      <a href="{{ post.url }}">
        {{ post.title }}
        <small>{{ post.date | date_to_string }}</small>
      </a>
      {% for tag in post.tags %}
      <a class="codinfox-tag-mark" href="/blog/tag/#{{ tag | slugify }}">{{ tag }}</a>
      {% endfor %}
    </h3>
  </li>
  {% endif %}
  {% endfor %}
</ul>
{% endfor %}

<h2 id="no-categories">No categories</h2>
<ul class="codinfox-categories-list">
  {% for post in site.posts %}
  {% unless post.categories %}
  <li>
    <h3>
      <a href="{{ post.url }}">
        {{ post.title }}
        <small>{{ post.date | date_to_string }}</small>
      </a>
      {% for tag in post.tags %}
      <a class="codinfox-tag-mark" href="/blog/tag/#{{ tag | slugify }}">{{ tag }}</a>
      {% endfor %}
    </h3>
  </li>
  {% endunless %}
  {% endfor %}
</ul>

</div>