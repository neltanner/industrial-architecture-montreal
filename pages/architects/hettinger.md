---
title: Hettinger
layout: about
permalink: /hettinger.html
# include CollectionBuilder info at bottom
# credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{%- assign items = site.data[site.metadata] -%}

{% for item in items %}
{% if item.architect contains "Reeves" %}
{{item.architect}}
{{item.birthdate}}
{% endif %}
{% endfor %}