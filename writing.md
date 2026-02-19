---
title: Writing
permalink: /writing/
---

## Blog
{% for post in site.posts %}
- <a href="{{ post.url }}">{{ post.title }}</a> <span class="meta">· {{ post.date | date: "%b %d, %Y" }}</span>
{% endfor %}

<hr>

## Newsletter
My newsletter lives on Substack: **[Read / Subscribe here](YOUR_SUBSTACK_LINK)**.
