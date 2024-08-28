---
layout: page
title: Posts
permalink: /posts/
---
## All posts:
<ul>
    {% for post in site.posts %}
        <li>
            <a href="/milessic{{ post.url }}" class="postLink">{{ post.title }}</a>
            <span>{{ post.date | date: "%B %d, %Y" }}</span>
        </li>
    {% endfor %}
</ul>

