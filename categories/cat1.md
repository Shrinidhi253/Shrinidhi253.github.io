---
layout: page
permalink: /cat1/
---

# All cat1 posts

{% for post in site.categories.cat1 %}
  <a href="{{ post.url }}">{{ post.title }}</a>
{% endfor %}