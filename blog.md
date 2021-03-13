---
title: Blog
---
Every so often, I may write a review of an album or band I listened to, something I watched, a book I read, or a game I played. I may also blog about science or general reflections about life.

{% for post in site.posts %}
* [{{ post.title }}]({{ post.url }})
{% endfor %}
