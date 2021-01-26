---
layout: splash
title: Projects
permalink: /projects/
---
{% for project in site.projects%}
<a href="{{project.url}}">{{project.url}}</a>
{% endfor %}