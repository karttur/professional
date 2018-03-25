---
layout: publication
title: SWAMP
excerpt: "An archive of wetland mapping (SWAMP) publications"
search_omit: true
share: true

---

The Sustainable Wetlands Adaptation and Mitigation Program (SWAMP) is a collaborative effort by the Center for International Forestry Research (CIFOR), the USDA Forest Service (USFS) and Oregon State University with support from the US Agency for International Development (USAID). SWAMP evolved from a multi-stakeholder exercise called the Tropical Wetlands Initiative for Climate Adaptation and Mitigation (TWINCAM), when the group was called to respond to a variety of challenges requested by stakeholders, ranging from local to global imperatives of sustainable wetlands management.

I have worked for SWAMP (TWINCAMP) as an independent researcher since 2012, focusing on mapping and monitoring of global pantropical wetlands and peatlands.

### Journal articles

<ul class="post-list">
{% for post in site.categories.journal %}
  {% if post.projectid == "swamp" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}  
</ul>

### Refereed chapters

<ul class="post-list">
{% for post in site.categories.refereechapter %}
  {% if post.projectid == "swamp" %}
    {% include publication.html %}
  {% endif %}
{% endfor %}
</ul>

### Institutional report

<ul class="post-list">
{% for post in site.categories.report %}
  {% if post.projectid == "swamp" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}  
</ul>

### Conference Processedings

<ul class="post-list">
{% for post in site.categories.conference %}
  {% if post.projectid == "swamp" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}  
</ul>

### Presentations

<ul class="post-list">
{% for post in site.categories.talk %}
  {% if post.projectid == "swamp" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}  
</ul>

### Posters

<ul class="post-list">
{% for post in site.categories.poster %}
  {% if post.projectid == "swamp" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}  
</ul>
