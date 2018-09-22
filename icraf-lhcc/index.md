---
layout: resume
title: Kenya Farmer Field School
excerpt: "An archive of Kenya Farmer Field School publications"
search_omit: true
share: true
---

Using Farmer Field Schools Approaches to Overcome Land Degradation in Agro-Pastoral Areas of Kenya. Land degradation assessment – Baseline survey on spatial analysis of land cover / degradation trends and Toolkit Development.

Within the project I created training DVDs at district level (Mberee, Mwingi and Narok districts), including field work and local dissemination. The complete DVD structure and data was produced from avenue scripts (ArcView scripting language) using html, xml and javascript. And the DVDs were used for local training and freely distributed. Neither ArcView (including avenue), nor some of the javascript solutions, are supported any longer.

### Report

<ul class="post-list">
{% for post in site.categories.report %}
  {% if post.projectid == "kenya-ffs" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

### Training

<span style="font-size: 80%;">
The training modules are part of the DVD publications. The spatial data (GIS layers) linked and referred to in the training modules are not available online.
</span>

<ul class="post-list">
{% for post in site.categories.training %}
  {% if post.projectid == "kenya-ffs" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

### Training DVD

<span style="font-size: 80%;">
The data and software available on the orginal training DVDs are not available online, only the report an the training lessons are available from above.
</span>

<ul class="post-list">
{% for post in site.categories.DVD %}
  {% if post.projectid == "kenya-ffs" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

### Images

<ul class="post-list">
{% for post in site.categories.images %}
  {% if post.projectid == "kenya-ffs" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>
