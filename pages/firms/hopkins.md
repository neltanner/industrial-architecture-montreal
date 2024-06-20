---
title: Hopkins
layout: about
permalink: /hopkins.html
# include CollectionBuilder info at bottom
# credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{%- assign items = site.data.firms -%}

{% for item in items %}
{% if item.title contains "J.W. & E.C. Hopkins" %}
{{item.title}}
{{item.firmdates}}
{{item.firmlocation}}
{{item.notes}}
{% endif %}
{% endfor %}