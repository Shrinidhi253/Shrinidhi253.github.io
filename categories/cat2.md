---
layout: page
---

# All cat2 posts

{% for post in site.categories.cat2 %}
  <a href="{{ post.url }}">{{ post.title }}</a>
{% endfor %}