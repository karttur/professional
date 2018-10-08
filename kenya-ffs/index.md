---
layout: resume
title: Farmer Field Schools
excerpt: "An archive of Farmer Field Schools training material"
search_omit: true
share: true
---

Using Farmer Field Schools Approaches to Overcome Land Degradation in Agro-Pastoral Areas of Kenya. Land degradation assessment – Baseline survey on spatial analysis of land cover / degradation trends and Toolkit Development.

<h1 class='foot-description'></h1>
<h1 class='foot-description'>Report</h1>

<ul class="post-list">
{% for post in site.categories.report %}
  {% if post.projectid == "kenya-ffs" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

<h1 class='foot-description'></h1>
<h1 class='foot-description'>Training</h1>

<ul class="post-list">
{% for post in site.categories.assignment %}
  {% if post.projectid == "kenya-ffs" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>
