---
layout: resume
title: Publications
excerpt: "An archive of articles sorted by publication type and date."
search_omit: true
share: true
---
Click on source (or icon) to get online pdf versions (articles with no icon are not available online), or click the title to see the complete reference and abstract.

<h1 class='foot-description'></h1>
<h1 class='foot-description'>Journal articles</h1>

<ul class="post-list">
{% for post in site.categories.journal %}
    {% include publication.html post=post %}
{% endfor %}  
</ul>

<h1 class='foot-description'></h1>
<h1 class='foot-description'>Atlas</h1>

<ul class="post-list">
{% for post in site.categories.atlas %}
    {% include publication.html post=post %}
{% endfor %}  
</ul>

<h1 class='foot-description'></h1>
<h1 class='foot-description'>Book chapters</h1>

<ul class="post-list">
{% for post in site.categories.refereechapter %}
    {% include publication.html post=post %}
{% endfor %}  
</ul>

<h1 class='foot-description'></h1>
<h1 class='foot-description'>JScientific reports</h1>

<ul class="post-list">
{% for post in site.categories.report %}
    {% include publication.html post=post %}
{% endfor %}  
</ul>

<h1 class='foot-description'></h1>
<h1 class='foot-description'>Conference proceedings</h1>

<ul class="post-list">
{% for post in site.categories.conference %}
    {% include publication.html post=post %}
{% endfor %}  
</ul>

<h1 class='foot-description'></h1>
<h1 class='foot-description'>Popular</h1>

<ul class="post-list">
{% for post in site.categories.popular %}
    {% include publication.html post=post %}
{% endfor %}  
</ul>
