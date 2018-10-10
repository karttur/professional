---
layout: resume
title: Head and Senior Lecturer, Geoinformatics, Department of Earch Sciences, Uppsala University.
excerpt: "An archive of teaching material in Geoinformatics."
search_omit: true
share: true

---
From August 1998 to April 2000 I was the head of the Geoinformatics unit at the Department of Earth Sciences, Uppsala University. My primary duty was to reorganize the Geoinformatics unit and create a new curricula integrating Geoinformatics courses with the thematic Earth sciences represented at the department. I also created distance learning courses over the internet, and supervised MSc students. I assisted in attracted funding for research projects, but left my position before the projects commenced. My contacts at Uppsala University allowed me to later attract funding for a [project on Lake Kyoga](../lakekyoga) (while working for ICRAF in Uganda), together with local partners in Uganda. I wrote the proposal, and I led and co-ordinated the Lake Kyoga project, but it had to be officially hosted by Uppsala University. During my time in South Africa and Uganda, I also took on [supervision of MSc students](../supervision) from Uppsala University.

While at UU I was responsible for the following courses:

- __GIS MN 1__, basic course in Geographic Information Systems (GIS) for students in Earth sciences
- __GIS MN 2__, advanced course in GIS for students in Earth sciences
- __GIS MN 1 distance__, web-based basic course in GIS for general students
- __GIS MN 2 distance__, web-based advanced course in GIS for general students
- __Distributed modelling with GIS__, course for civil engineering students
- __Geography C, methods and GIS__, basic course in GIS for geography students

The lectures that I created were analogue, course assignments and projects, however, were created as digital documents. An older version of the assignments and projects is available [here](http://www.karttur.com/private/teaching/index.htm).

<h1 class='foot-description'></h1>
<h1 class='foot-description'>Training assignments</h1>

<ul class="post-list">
{% for post in site.categories.assignment %}
  {% if post.projectid == "uu" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

<h1 class='foot-description'></h1>
<h1 class='foot-description'>Training projects</h1>

<ul class="post-list">
{% for post in site.categories.pblproject %}
  {% include publication.html post=post %}    
{% endfor %}
</ul>
