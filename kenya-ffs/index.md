---
layout: resume
title: Kenya Farmer Field School
excerpt: "An archive of Kenya Farmer Field School publications"
search_omit: true
share: true

---

Using Farmer Field Schools Approaches to Overcome Land Degradation in Agro-Pastoral Areas of Kenya. Land degradation assessment – Baseline survey on spatial analysis of land cover / degradation trends and Toolkit Development.

Within the project I created training DVDs at district level (Mberee, Mwingi and Narok districts), including field work and local dissemination. The complete DVD structure and data was produced from avenue scripts (ArcView scripting language) using html, xml and javascript. And the DVDs were used for local training and freely distributed. Neither ArcView (including avenue), nor some of the javascript solutions, are supported any longer.

### Report

<span style="font-size: 80%;">
The report is also a part of the DVD publications below. The training modules  linked and referred to in the report are the same as listed below.
</span>

<ul class="post-list">
{% for post in site.categories.report %}
  {% if post.projectid == "kenya-ffs" %}
    <li><article>
    {% if post.authors %}
      <span style="font-size: 80%; display: block;">{{ post.authors | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }},
      {% if post.source %}
        {% if post.doiurl %}
          <a href="{{ post.doiurl }}">
          {{ post.source }}
          </a>
        {% else %}
          {{ post.source }}
        {% endif %}
      {% endif %}
      (<span style="font-weight: bold;"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%Y" }}</time></span>).
      </span>
    {% endif %}
    <a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a>
    </article></li>
  {% endif %}
{% endfor %}
</ul>


### DVD publications
<span style="font-size: 80%;">
The links to the three project DVD´s only show the front page that open with each DVD. The DVD documents (project report and training modules) are the same as those listed on this page. The spatial data (GIS layers) are not available online.
</span>
<ul class="post-list">
{% for post in site.categories.DVD %}
  {% if post.projectid == "kenya-ffs" %}
    <li><article>
    {% if post.authors %}
      <span style="font-size: 80%; display: block;">{{ post.authors | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }},
      {% if post.source %}
        {% if post.doiurl %}
          <a href="{{ post.doiurl }}">
          {{ post.source }}
          </a>
        {% else %}
          {{ post.source }}
        {% endif %}
      {% endif %}
      (<span style="font-weight: bold;"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%Y" }}</time></span>).
      </span>
    {% endif %}
    <a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a>
    </article></li>
  {% endif %}
{% endfor %}
</ul>

### Training

<span style="font-size: 80%;">
The training modules are part of the DVD publications above. The spatial data (GIS layers) linked and referred to in the training modules are not available online.
</span>

<ul class="post-list">
{% for post in site.categories.training %}
  {% if post.projectid == "kenya-ffs" %}
    <li><article>
    {% if post.authors %}
      <span style="font-size: 80%; display: block;">{{ post.authors | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }},
      {% if post.source %}
        {% if post.doiurl %}
          <a href="{{ post.doiurl }}">
          {{ post.source }}
          </a>
        {% else %}
          {{ post.source }}
        {% endif %}
      {% endif %}
      (<span style="font-weight: bold;"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%Y" }}</time></span>).
      </span>
    {% endif %}
    <a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a>
    </article></li>
  {% endif %}
{% endfor %}
</ul>

### Images

Not yet available

<ul class="post-list">
{% for post in site.categories.images %}
  {% if post.projectid == "kenya-ffs" %}
    <li><article>
    {% if post.authors %}
      <span style="font-size: 80%; display: block;">{{ post.authors | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }},
      {% if post.source %}
        {% if post.doiurl %}
          <a href="{{ post.doiurl }}">
          {{ post.source }}
          </a>
        {% else %}
          {{ post.source }}
        {% endif %}
      {% endif %}
      (<span style="font-weight: bold;"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%Y" }}</time></span>).
      </span>
    {% endif %}
    <a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a>
    </article></li>
  {% endif %}
{% endfor %}
</ul>
