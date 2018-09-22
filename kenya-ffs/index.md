---
layout: resume
title: Land Health Surveillance for Targeting Climate Change and Ecosystem Management Interventions in Africa
excerpt: "An archive of Land Health Surveillance for Targeting Climate Change and Ecosystem Management Interventions in Africa publications"
search_omit: true
share: true
---

Pilot study for developing management intervention tools based on spatial mapping and monitoring of natural resources from remote sensing data and other publicly available spatial data sources. Results included automated work flows for spatial data processing and definition of suitable indexes and indicators to use for management interventions.

### Report

<ul class="post-list">
{% for post in site.categories.report %}
  {% if post.projectid == "icraf-lhcc" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>
