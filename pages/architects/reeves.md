---
title: Reeves
layout: about
permalink: /reeves.html
# include CollectionBuilder info at bottom
# credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{%- assign items = site.data[site.architects] -%}

{% for item in items %}
{% if item.title contains "Reeves" %}
{{item.title}}
{{item.birthdate}}
{{item.active}}
{% endif %}
{% endfor %}