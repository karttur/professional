---
layout: publication
title: Publications
excerpt: "An archive of articles sorted by date."
search_omit: true
share: true

---

<h1 class='foot-description'>Journal articles</h1>


<ul class="post-list">
{% for post in site.categories.journal %}
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
<h1 class='foot-description'>Atlas</h1>

<ul class="post-list">
{% for post in site.categories.atlas %}
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
<h1 class='foot-description'>Refereed chapters</h1>

<ul class="post-list">
{% for post in site.categories.refereechapter %}
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
<h1 class='foot-description'>Refereed scientific reports</h1>

<ul class="post-list">
{% for post in site.categories.report %}
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
<h1 class='foot-description'>Conference proceedings</h1>

<ul class="post-list">
{% for post in site.categories.conference %}
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
