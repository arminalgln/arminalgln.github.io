---
layout: posts
title: Blog
permalink: /posts/
---
{% for post in site.posts%}
<a href="{{post.url}}">{{post.url}}</a>
{% endfor %}