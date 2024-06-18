---
title: Amos
layout: about
permalink: /amos.html
# include CollectionBuilder info at bottom
# credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{%- assign items = site.data[site.metadata] -%}

{% for item in items %}
{% if item.architect contains "Amos" %}
{{item.architect}}
{{item.birthdate}}
{% endif %}
{% endfor %}