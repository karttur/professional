---
layout: resume
title: Community training
excerpt: "Various short community training courses and projects"
search_omit: true
share: true
---

## Regional GIS Training (RELMA, Nairobi, 2003)

Short training course with thematic focus on Natural Resources Management (NRM). The course centered around 4 exercises introducing Geographical Information Systems (GIS) and Remote Sensing (RS).The exercises were built on two free GIS programs; ArcExplorer (created by ESRI as the free viewer version of ArcView) and DIVA-GIS (created by the International Potato Center).

<ul class="post-list">
{% for post in site.categories.training %}
  {% if post.projectid == "sahel" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

## Farmer Field School (ICRAF, Nairobi, 200t)

Using Farmer Field Schools Approaches to Overcome Land Degradation in Agro-Pastoral Areas of Kenya. Land degradation assessment – Baseline survey on spatial analysis of land cover / degradation trends and Toolkit Development.

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

<ul class="post-list">
{% for post in site.categories.training %}
  {% if post.projectid == "sahel" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

## Lake Tanganyika Regional Integrated Management Project (UNDD/ICRAF, Lake Tanganyika, 2010/2011)

A United Nations Development Programme (UNDP) / Global Environmental Facility (GEF) project covering the Lake Tanganyika riparian countries, Burundi, the Democratic Republic of Congo, Tanzania and Zambia.

I organized and led training workshops in Kenya, Tanzania, Zambia and the Democratic Republic of Congo (DRC). For the training in the latter three I led the development of a set of training lessons, that we then adjusted to cover national data at each training session.

<ul class="post-list">
{% for post in site.categories.training %}
  {% if post.projectid == "tanganyika" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>
