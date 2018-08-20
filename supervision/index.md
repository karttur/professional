---
layout: resume
title: Supervision
excerpt: "An archive of supervisions"
search_omit: true
share: true
---

As a lecturer and researcher at the Royal Institute of Technology (KTH) (Stockholm, Sweden) I supervised 10 MSc projects, two licentiate projects (see below) and one PhD project. The PhD project supervision continued after I left KTH, also because the PhD project geographical focus coincided with my post-doc studies - the Okavango inland delta in Botswana. While at Uppsala University I supervised three MSc projects, including supervisions done during my post-doc period at University of the Witwatersrand in South Africa.

<h1 class='foot-description'>PhD projects</h1>

<ul class="post-list">
{% for post in site.categories.phdthesis %}
    {% include publication.html post=post %}
{% endfor %}  
</ul>
<h1 class='foot-description'></h1>
<h1 class='foot-description'>Licentiate projects</h1>

In Sweden (and Finland) a licentiate degree is half way between an MSc and a PhD. It is nowadays becoming less common to take a licentiate degree with approximately one third of all doctoral students taking a licentiate in Sweden (fewer in Finland).

<ul class="post-list">
{% for post in site.categories.licthesis %}
    {% include publication.html post=post %}
{% endfor %}  
</ul>
<h1 class='foot-description'></h1>
<h1 class='foot-description'>MSc projects</h1>

<ul class="post-list">
{% for post in site.categories.mscthesis %}
    {% include publication.html post=post %}
{% endfor %}  
</ul>
