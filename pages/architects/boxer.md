---
title: Boxer, Frederick (Francois) Nepheau
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

<div class="container py-3">
    {% include item/breadcrumbs.html %}
    <h2 class="mb-3">{{ page.title }}{{ item.active }} </h2>
</div>

<div class="container py-3">
{% if item.birthdate %}
<dt>Birthdate:</dt>
<dd>{{item.birthdate}}</dd>
{% endif %}

{% if item.deathdate %}
<dt>Deathdate:</dt>
<dd>{{item.deathdate}}</dd>
{% endif %}

{% if item.education %}
<dt>Education:</dt>
<dd>{{item.education}}</dd>
{% endif %}

{% if item.birthplace %}
<dt>Birthplace:</dt>
<dd>{{item.birthplace}}</dd>
{% endif %}

{% if item.notes %}
<dt>Notes:</dt>
<dd>{{item.notes}}</dd>
{% endif %}
</div>

{% endif %}
{% endfor %}