---
layout: blog6
title: posts
permalink: /blog/
---

{% for post in site.posts %}	
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p><small><strong>{{ post.date | date: "%B %e, %Y" }}</strong> . {{ post.category }}</small></p>			
{% endfor %}