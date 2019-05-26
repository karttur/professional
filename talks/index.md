---
layout: resume
title: Talks and Poster presentations
excerpt: "Archive of talks and poster presentations"
search_omit: true
share: true

---

All presentations are available as pdf files (talks) or jgp images (posters). A few talks are also available as movies. Click on the title to get to the page where you can read, view or download the source file.

<h1 class='foot-description'></h1>
<h1 class='foot-description'>Talks</h1>

<ul class="post-list">
{% for post in site.categories.talk %}
  {% include publication.html post=post %}    
{% endfor %}
</ul>

<h1 class='foot-description'></h1>
<h1 class='foot-description'>Posters</h1>

<ul class="post-list">
{% for post in site.categories.poster %}
  {% include publication.html post=post %}    
{% endfor %}
</ul>
