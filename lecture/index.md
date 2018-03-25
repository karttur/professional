---
layout: publication
title: Teaching material
excerpt: "Archive of teaching material"
search_omit: true
share: true

---


<h2>Lectures</h2>

<h2 class='foot-description'>GIS Grundkurs (1n1651), KTH, Stockholm, Sweden.</h2>
<ul class="post-list">
  {% for post in site.categories.lecture-1n1651 %}
    <li><article>
    {% if post.authors %}
      <span style="font-size: 80%; display: block;">{{ post.authors | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }},
    {% if post.source %}
     {{ post.source }}
    {% endif %}
    (<span style="font-weight: bold;"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%Y" }}</time></span>).
    </span>
    {% endif %}
    <a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a>
    </article></li>
  {% endfor %}
</ul>

<h2 class='foot-description'></h2>
<h2 class='foot-description'>GIS i samhällsbyggnad (1n1654), KTH, Stockholm, Sweden.</h2>
<ul class="post-list">
  {% for post in site.categories.lecture-1n1654 %}
    <li><article>
    {% if post.authors %}
      <span style="font-size: 80%; display: block;">{{ post.authors | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }},
    {% if post.source %}
     {{ post.source }}
    {% endif %}
    (<span style="font-weight: bold;"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%Y" }}</time></span>).
    </span>
    {% endif %}
    <a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a>
    </article></li>
  {% endfor %}
</ul>

<h2 class='foot-description'></h2>
<h2 class='foot-description'>Geo visualisation (ag2412), KTH, Stockholm, Sweden.</h2>
<ul class="post-list">
  {% for post in site.categories.lecture-ag2412 %}
    <li><article>
    {% if post.authors %}
      <span style="font-size: 80%; display: block;">{{ post.authors | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }},
    {% if post.source %}
     {{ post.source }}
    {% endif %}
    (<span style="font-weight: bold;"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%Y" }}</time></span>).
    </span>
    {% endif %}
    <a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a>
    </article></li>
  {% endfor %}
</ul>
<h2 class='foot-description'></h2>
