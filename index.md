---
layout: default
---

<div class="hero">
    <h1>Welcome to Tech Insider</h1>
    <p>Exploring the latest in technology, gadgets, and innovation.</p>
</div>

<div class="posts-grid">
    {% for post in site.posts %}
    <article class="post-card">
        <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
        <p class="post-meta">{{ post.date | date: "%B %d, %Y" }} by {{ post.author | default: "Anonymous" }}</p>
        <p>{{ post.excerpt }}</p>
        <a href="{{ post.url }}" class="read-more">Read More</a>
    </article>
    {% endfor %}
</div>