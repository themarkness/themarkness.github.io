---
layout: default
title: Blog
date: 2017-01-01
---

{% for post in site.posts limit: 10 %}
<article class="post-preview">
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p class="post-date">{{ post.date | date: "%B %d, %Y" }}</p>
    
    {% if post.tags.size > 0 %}
    <div class="post-tags">
        {% for tag in post.tags %}
            <a href="{{ '/tag/' | append: tag | slugify | relative_url }}" class="tag">{{ tag }}</a>
        {% endfor %}
    </div>
    {% endif %}
    
    <div class="post-excerpt">
        {{ post.excerpt }}
    </div>
    
    <a href="{{ post.url }}" class="read-more">Read more →</a>
</article>

<hr>
{% endfor %}