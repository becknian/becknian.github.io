---
layout: default
---

# Welcome to My Tech Blog

Here are my latest posts:

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }})
{{ post.excerpt }}

---
{% endfor %}