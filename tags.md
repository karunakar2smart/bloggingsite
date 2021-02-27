---
layout:   post
title:    Tag
permalink: tags.html
image: /
datepublished: "2019-08-30"
datemodified: "2019-12-25"
---
{% comment%}
Here we generate all the tags.
{% endcomment%}

{% assign rawtags = "" %}
{% for post in site.posts %}
{% assign ttags = post.tags | join:'|' | append:'|' %}
{% assign rawtags = rawtags | append:ttags %}
{% endfor %}

{% assign rawtags = rawtags | split:'|' | sort %}

{% assign tags = "" %}

{% for tag in rawtags %}
{% if tag != "" %}

{% if tags == "" %}
{% assign tags = tag | split:'|' %}
{% endif %}

{% unless tags contains tag %}
{% assign tags = tags | join:'|' | append:'|' | append:tag | split:'|' %}
{% endunless %}
{% endif %}
{% endfor %}

<h1 class="page-title">
  <a href="/blog">Blog</a> | {{ page.title }}
</h1>
<br/>

<div class="posts">
<p>
{% for tag in tags %}
<a href="#{{ tag | slugify }}" class="codinfox-tag-mark"> {{ tag }} </a> &nbsp;&nbsp;
{% endfor %}

{% for tag in tags %}
<h2 id="{{ tag | slugify }}">{{ tag }}</h2>
<ul class="codinfox-category-list">
  {% for post in site.posts %}
  {% if post.tags contains tag %}
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