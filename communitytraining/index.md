---
layout: resume
title: Community training
excerpt: "Various short community training courses and projects"
search_omit: true
share: true
---

## Regional GIS Training (RELMA, Nairobi, 2003)

Short training course with thematic focus on Natural Resources Management (NRM). The course centered around 4 exercises introducing Geographical Information Systems (GIS) and Remote Sensing (RS).The exercises were built on two free GIS programs; ArcExplorer (created by ESRI as the free viewer version of ArcView) and DIVA-GIS (created by the International Potato Center).

### Training lessons

<ul class="post-list">
{% for post in site.categories.training %}
  {% if post.projectid == "sahel" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

## Farmer Field School (ICRAF, Nairobi, 200t)

Using Farmer Field Schools Approaches to Overcome Land Degradation in Agro-Pastoral Areas of Kenya. Land degradation assessment – Baseline survey on spatial analysis of land cover / degradation trends and Toolkit Development.

### Training lessons

<ul class="post-list">
{% for post in site.categories.training %}
  {% if post.projectid == "kenya-ffs" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

## West African Drylands (UNEP/ICRAF, Segou, 2008)

An Ecosystem Approach to Restoring West African Drylands and Improving Livelihoods through Agroforestry-based Land Management Interventions.

A United Nations Environment Programme (UNEP) project conducted in partnership with the World Agroforestry Centre (ICRAF), the Centre for Environmental Policy of the University of Florida, and the Governments of Burkina Faso, Mali, Mauritania, Niger and Senegal. The project is funded by the Government of Norway.

### Training lessons

<ul class="post-list">
{% for post in site.categories.training %}
  {% if post.projectid == "sahel" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>
