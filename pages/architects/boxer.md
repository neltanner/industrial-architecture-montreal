---
title: Boxer
layout: about
permalink: /boxer.html
# include CollectionBuilder info at bottom
# credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{%- assign items = site.data.architects -%}

{% for item in items %}
{% if item.title contains "Boxer" %}
{{item.title}}
{{item.birthdate}}
{{item.deathdate}}
{{item.active}}
{{item.education}}
{{item.birthplace}}
{{item.notes}}
{% endif %}
{% endfor %}