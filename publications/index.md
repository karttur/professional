---
layout: publication
title: Publications
excerpt: "An archive of articles sorted by publication type and date."
search_omit: true
share: true
---
Click on source icon to get online pdf versions (articles with no icon are not available online), or click the title to see abstract.

### Journal articles

<ul class="post-list">
{% for post in site.categories.journal %}
    {% include publication.html post=post %}
{% endfor %}  
</ul>

### Atlas

<ul class="post-list">
{% for post in site.categories.atlas %}
    {% include publication.html post=post %}
{% endfor %}  
</ul>

### Book chapters

<ul class="post-list">
{% for post in site.categories.refereechapter %}
    {% include publication.html post=post %}
{% endfor %}  
</ul>

### Scientific reports

<ul class="post-list">
{% for post in site.categories.report %}
    {% include publication.html post=post %}
{% endfor %}  
</ul>

### Conference proceedings

<ul class="post-list">
{% for post in site.categories.conference %}
    {% include publication.html post=post %}
{% endfor %}  
</ul>
