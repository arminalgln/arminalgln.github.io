---
layout: splash
title: Publications
permalink: /publications/
---
{% for paper in site.papers%}
<a href="{{paper.url}}">{{paper.url}}</a>
{% endfor %}