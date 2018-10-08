---
layout: resume
title: West African Drylands Project
excerpt: "An archive of Lake sahel publications"
search_omit: true
share: true

---

An Ecosystem Approach to Restoring West African Drylands and Improving Livelihoods through Agroforestry-based Land Management Interventions. A United Nations Environment Programme (UNEP) project conducted in partnership with the World Agroforestry Centre (ICRAF), the Centre for Environmental Policy of the University of Florida, and the Governments of Burkina Faso, Mali, Mauritania, Niger and Senegal. Project funded by the Government of Norway.

My part in the project included development of land degradation monitoring from time series of satellite images, general landscape mapping and historical climate change analysis.

<h1 class='foot-description'></h1>
<h1 class='foot-description'>Journal articles</h1>

<ul class="post-list">
{% for post in site.categories.journal %}
  {% if post.projectid == "sahel" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

<h1 class='foot-description'></h1>
<h1 class='foot-description'>Atlas</h1>

<ul class="post-list">
{% for post in site.categories.atlas %}
  {% if post.projectid == "sahel" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

<h1 class='foot-description'></h1>
<h1 class='foot-description'>Reports</h1>

<ul class="post-list">
{% for post in site.categories.report %}
  {% if post.projectid == "sahel" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

<h1 class='foot-description'></h1>
<h1 class='foot-description'>Presentations</h1>

<ul class="post-list">
{% for post in site.categories.talk %}
  {% if post.projectid == "sahel" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

<h1 class='foot-description'></h1>
<h1 class='foot-description'>Lectures</h1>

<ul class="post-list">
{% for post in site.categories.lecture %}
  {% if post.projectid == "sahel" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>


<h1 class='foot-description'></h1>
<h1 class='foot-description'>Training DVD</h1>

<ul class="post-list">
{% for post in site.categories.DVD %}
  {% if post.projectid == "sahel" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

<h1 class='foot-description'></h1>
<h1 class='foot-description'>Training lessons</h1>

<ul class="post-list">
{% for post in site.categories.assignment %}
  {% if post.projectid == "sahel" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

<h1 class='foot-description'></h1>
<h1 class='foot-description'>Movie</h1>

<ul class="post-list">
{% for post in site.categories.movie %}
  {% if post.projectid == "sahel" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

<h1 class='foot-description'></h1>
<h1 class='foot-description'>Images</h1>

<ul class="post-list">
{% for post in site.categories.images %}
  {% if post.projectid == "sahel" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>
