---
layout: resume
title: Lake Tanganyika Regional Integrated Management Project.
excerpt: "An archive of Lake Tanganyika publications"
search_omit: true
share: true

---
A United Nations Development Programme (UNDP) / Global Environmental Facility (GEF) project covering the Lake Tanganyika riparian countries, Burundi, the Democratic Republic of Congo, Tanzania and Zambia.

Within the project I organized and led training workshops in Kenya, Tanzania, Zambia and the Democratic Republic of Congo (DRC). I also held the training modules on spatial data analysis and land degradation in each project country.

### Presentations

<ul class="post-list">
{% for post in site.categories.talk %}
  {% if post.projectid == "tanganyika" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

### Training

<ul class="post-list">
{% for post in site.categories.training %}
  {% if post.projectid == "tanganyika" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

### Movie

Not yet available

<ul class="post-list">
{% for post in site.categories.popular %}
  {% if post.projectid == "tanganyika" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

### Images

Not yet available

<ul class="post-list">
{% for post in site.categories.images %}
  {% if post.projectid == "tanganyika" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>
