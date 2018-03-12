---
layout: publication
title: Teaching material
excerpt: "An archive of teaching material"
search_omit: true
share: true

---

<h1 class='foot-description'>Lectures</h1>

<a href="http://www.karttur.com/private/teaching/index.htm">
Please use this link to get a page that contains a list of lectures with links to pdf version of each lecture. Some of the lectures are in Swedish and some in English.
</a>

<ul class="post-list">
{% for post in site.categories.lectures %}
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
  {% endfor %}
</ul>

<h1 class='foot-description'></h1>
<h1 class='foot-description'>Exercises</h1>

<a href="http://www.karttur.com/private/teaching/index.htm">
Please use this link to get a page that contains a list of exercises that I developed for teaching spatial data processing and analysis. Each exercise is available as a pdf file. Some of the exercises are in Swedish and some in English. The latter include exercises specifically developed for different professional groups in Africa.
</a>

<ul class="post-list">
{% for post in site.categories.exercises %}
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
  {% endfor %}
</ul>

<h1 class='foot-description'></h1>
<h1 class='foot-description'>Teaching projects</h1>

<a href="http://www.karttur.com/private/teaching/index.htm">
Please use this link to get a page that contains a list of project instructions that I developed for teaching spatial data processing and analysis (you have to scroll to the bottom of the page to get to the projects). Each project is available as a pdf file, and all project instructions are in English. 
</a>

<ul class="post-list">
{% for post in site.categories.teachingprojects %}
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
  {% endfor %}
</ul>
