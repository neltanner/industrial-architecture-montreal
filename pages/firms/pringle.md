---
title: T. Pringle & Son (Engineers)
layout: about
permalink: /pringle.html
# include CollectionBuilder info at bottom
# credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{%- assign items = site.data.firms -%}

{% for item in items %}
{% if item.title contains "T. Pringle & Son" %}
{{item.title}}
{{item.firmdates}}
{{item.firmlocation}}
{{item.notes}}
{% endif %}
{% endfor %}