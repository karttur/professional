---
layout: resume
title: Farmer Field Schools
excerpt: "An archive of Farmer Field Schools training material"
search_omit: true
share: true
---

Using Farmer Field Schools Approaches to Overcome Land Degradation in Agro-Pastoral Areas of Kenya. Land degradation assessment – Baseline survey on spatial analysis of land cover / degradation trends and Toolkit Development.

### Report

<ul class="post-list">
{% for post in site.categories.report %}
  {% if post.projectid == "kenya-ffs" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

### Training lessons

<ul class="post-list">
{% for post in site.categories.training %}
  {% if post.projectid == "kenya-ffs" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>
