---
layout: resume
title: Talks and Poster presentations
excerpt: "Archive of talks and poster presentations"
search_omit: true
share: true

---

All presentations are available as pdf files (talks) or jgp images (posters). Click on the title to get to the page where you can read or download the source file.

### Talks

<ul class="post-list">
{% for post in site.categories.talk %}
  {% include publication.html post=post %}    
{% endfor %}
</ul>

### Posters

<ul class="post-list">
{% for post in site.categories.poster %}
  {% include publication.html post=post %}    
{% endfor %}
</ul>
