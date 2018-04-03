---
layout: resume
title: Lake Kyoga, Uganda
excerpt: "An archive of Lake Kyoga publications"
search_omit: true
share: true

---

Kyoga is a shallow lake north of Lake Victoria in Uganda. In 2003 I raised funding for a 2 year project on "Integrated management of Lake Kyoga natural resources". Project partners included Uppsala University (Sweden), and Fisheries Resoruces Research Institute (FIRRI) Department of Water Development in Uganda. The project was financed by the Swedish International Development Cooperation Agency (SIDA).

### Conference Proceedings

<ul class="post-list">
{% for post in site.categories.conference %}
  {% if post.projectid == "kyoga" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}  
</ul>

### Presentations

<ul class="post-list">
{% for post in site.categories.talk %}
  {% if post.projectid == "kyoga" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}  
</ul>

### Posters

<ul class="post-list">
{% for post in site.categories.poster %}
  {% if post.projectid == "kyoga" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

### Movie

<ul class="post-list">
{% for post in site.categories.movie %}
  {% if post.projectid == "kyoga" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

### Images

<ul class="post-list">
{% for post in site.categories.image %}
  {% if post.projectid == "kyoga" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>
