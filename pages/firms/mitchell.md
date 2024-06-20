---
title: Mitchell & Creighton
layout: about
permalink: /mitchell.html
# include CollectionBuilder info at bottom
# credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{%- assign items = site.data.firms -%}

{% for item in items %}
{% if item.title contains "Mitchell & Creighton" %}
{{item.title}}
{{item.firmdates}}
{{item.firmlocation}}
{{item.notes}}
{% endif %}
{% endfor %}