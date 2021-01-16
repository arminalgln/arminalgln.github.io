---
layout: splash
title: Research
permalink: /projects/
---
{% for project in site.projects%}
<a href="{{project.url}}">{{project.url}}</a>
{% endfor %}