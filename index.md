---
title: Home
description: >
  The official Hydejack blog. Version updates, example content and how-to guides on how to blog with Jekyll.
  Open `index.html` to edit this text.
cover: true
---


# Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>