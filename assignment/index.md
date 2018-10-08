---
layout: resume
title: Training assignments
excerpt: "Archive of training exercises"
search_omit: true
share: true
---

Training assignments that I developed between 1999 and 2010. All assignments center on the use of spatial data and Geographical Information Systems (GIS). Below the assignments are grouped by the forum or geographical region they were developed for.

### Uppsala University

<ul class="post-list">
{% for post in site.categories.assignment %}
  {% if post.projectid == "uu" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

### RELMA Regional GIS Training, East Africa

<ul class="post-list">
{% for post in site.categories.assignment %}
  {% if post.projectid == "relma" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

### Okavango

<ul class="post-list">
{% for post in site.categories.assignment %}
  {% if post.projectid == "okavango" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

### Rwenzori landcover and glacier change

<ul class="post-list">
{% for post in site.categories.assignment %}
  {% if post.projectid == "rwenzori" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

### Farmer Field School, Kenya

<ul class="post-list">
{% for post in site.categories.assignment %}
  {% if post.projectid == "kenya-ffs" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

### West African Drylands

<ul class="post-list">
{% for post in site.categories.assignment %}
  {% if post.projectid == "sahel" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

### Lake Tanganyika

<ul class="post-list">
{% for post in site.categories.assignment %}
  {% if post.projectid == "tanganyika" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>
