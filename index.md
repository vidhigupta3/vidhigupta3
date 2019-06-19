---
title: Home
description: >
  The official Hydejack blog. Version updates, example content and how-to guides on how to blog with Jekyll.
  Open `index.html` to edit this text.
cover: true
---

{% for post in site.posts %}	
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p><small><strong>{{ post.date | date: "%B %e, %Y" }}</strong> . {{ post.category }} . <a href="http://erjjones.github.com{{ post.url }}#disqus_thread"></a></small></p>			
{% endfor %}	