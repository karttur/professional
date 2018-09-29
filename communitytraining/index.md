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
