---
layout: resume
title: Head and Senior Lecturer, Geoinformatics, Department of Earch Sciences, Uppsala University.
excerpt: "An archive of teaching material in Geoinformatics."
search_omit: true
share: true

---
From August 1998 to April 2000 I was the head of the Geoinformatics unit at the Department of Earth Sciences, Uppsala University. My primary duty was to reorganize the Geoinformatics unit and create a new curricula integrating Geaoinformatics courses with the thematic Earth sciences represented at the department. I also created distance learning courses over the internet, and supervised MSc students. I assisted in attracted funding for research projects, but left my position before the projects commenced. My contacts at Uppsala University allowed me to later attract funding for a project on Lake Kyoga (while working for ICRAF in Uganda), together with local partners in Uganda. I wrote the proposal for Lake Kyoga, and I led and co-ordinated the project, but it had to be officially hosted by Uppsala University. During my time in South Africa and Uganda, I also took on supervision of MSc students from Uppsala University.

This page is under construction but some of the material from my period in Uppsala is available [here](http://www.karttur.com/private/teaching/index.htm).

### Training assignments

<ul class="post-list">
{% for post in site.categories.assignemnt %}
  {% if post.projectid == "uu" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

### Training projects

<ul class="post-list">
{% for post in site.categories.pblproject %}
  {% include publication.html post=post %}    
{% endfor %}
</ul>
