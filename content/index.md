---
data: posts.posts
layout: index.njk
---

![profile-photo.jpg](/assets/profile-photo.png)

# Hi. I'm Makayla.

This is some placeholder text.

## A bit about my work.

This is also some placeholder text.

{% for post in posts.posts | limit(5) %}
[{{post.title}}](/blog/{{post.path}})
{% endfor %}
