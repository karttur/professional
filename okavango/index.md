---
layout: resume
title: Okavango post-doc studies (still continuing).
excerpt: "An archive of Okavango publications"
search_omit: true
share: true
---
1999 I got a post-doc scholarship from the Swedish Royal Academy of Sciences, allowing me to move to South Africa and start as a post-doc with the University of the Witwatersrand (Wits) in Johannesburg. My studies focused on the Okavango swamps in Botswana, but also other regional wetlands. I stayed at Wits for two years, and also worked for a few months with the tourist industry in the Okavango.

I have since then used my data and knowledge about the Okavango in many other studies, including my efforts in [mapping and monitoring global tropical wetlands and peatlands](../swamp/).

I worked with tourist industry in the Okavango, training the guides in the geological and sedimentological processes sustaining the Okavango. I also developed a web-based and interactive map interface using google maps for the tourist industry, and I created and led training sessions in using geoinformatics.

### Journal articles

<ul class="post-list">

{% for post in site.categories.journal %}
  {% if post.okavango %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}

{% for post in site.categories.journal %}
  {% if post.projectid == "okavango" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}  
</ul>

### Refereed chapters

<ul class="post-list">
{% for post in site.categories.refereechapter %}
  {% if post.okavango %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}

{% for post in site.categories.refereechapter %}
  {% if post.projectid == "okavango" %}
    {% include publication.html %}
  {% endif %}
{% endfor %}
</ul>

### Conference Proceedings

<ul class="post-list">
{% for post in site.categories.conference %}
  {% if post.okavango %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
{% for post in site.categories.conference %}
  {% if post.projectid == "okavango" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}  
</ul>

### Presentations

<ul class="post-list">
{% for post in site.categories.talk %}
  {% if post.okavango %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
{% for post in site.categories.talk %}
  {% if post.projectid == "okavango" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}  
</ul>

### Lectures

<ul class="post-list">
{% for post in site.categories.lecture %}
  {% if post.okavango %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
{% for post in site.categories.lecture %}
  {% if post.projectid == "okavango" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}  
</ul>

### Posters

<ul class="post-list">
{% for post in site.categories.poster %}
  {% if post.projectid == "okavango" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}  
</ul>

### Popular
Under construction
<ul class="post-list">
{% for post in site.categories.popular %}
  {% if post.projectid == "okavango" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}  
</ul>

### Training

<ul class="post-list">
{% for post in site.categories.training %}
  {% if post.projectid == "okavango" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}  
</ul>

### Images
Under construction
<ul class="post-list">
{% for post in site.categories.images %}
  {% if post.projectid == "okavango" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}  
</ul>
