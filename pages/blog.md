---
layout: inner2
title: Sprout Technology Blog  
---

<h1 class="blog-title">Recent Post</h1>

<ul class="posts"> 
  {% for post in site.posts limit:5 %}
    <li>
			<h3>{{ post.title}}</h3>
			<p>Posted on {{ post.date | date_to_long_string }}. </p> 
			{{ post.content }}
		</li>
  {% endfor %}
</ul>