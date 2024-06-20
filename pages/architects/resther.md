---
title: Resther
layout: about
permalink: /resther.html
# include CollectionBuilder info at bottom
# credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{%- assign items = site.data[site.architects] -%}

{% for item in items %}
{% if item.architect contains "Rester" %}
{{item.architect}}
{{item.birthdate}}
{% endif %}
{% endfor %}