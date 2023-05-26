---
layout: home
---

Welcome to my Minimal Mistakes demo page! This is a simple example page showcasing the features of the Minimal Mistakes theme.

## Latest Blog Posts

{% for post in site.posts %}
  ### [{{ post.title }}]({{ post.url }})
  {{ post.excerpt }}
{% endfor %}
