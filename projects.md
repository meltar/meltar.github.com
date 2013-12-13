---
layout: page
title: "Projects"
name: Melissa Holmes
tagline: Rails Developer
description: ""
group: navigation
---
{% include JB/setup %}


{% assign group = 'projects' %}

{% for node in site.pages %}
	{% if group == node.group %}
		{{ node.title }}
	{% endif %}
{% endfor %}

{% assign group = nil %}
