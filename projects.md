---
layout: page
title: "Projects"
name: Melissa Holmes
tagline: Rails Developer
description: ""
group: navigation
---
{% include JB/setup %}

<ul class="project">
	{% for project in site.projects %}
    <li><span>{{ project.name }}</span> &raquo; <a href="{{ project.source_url }}">{{ project.name }} Source</a></li>
	{% endfor %}
</ul>
