---
layout: publication
title: Rwenzori
excerpt: "An archive of Rwenzori publications"
search_omit: true
share: true

---

In June 2006 I took part in the 100 year anniversary of the first climb to the summit of Mount Rwenzori (The Mountains of the Moon) straddling the border between Uganda and the Democratic Republic of Congo (DRC).

### Presentations

<ul class="post-list">
{% for post in site.categories.talk %}
  {% if post.projectid == "rwenzori" %}
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

### Posters

<ul class="post-list">
{% for post in site.categories.poster %}
  {% if post.projectid == "rwenzori" %}
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

### Movie

<ul class="post-list">
{% for post in site.categories.popular %}
  {% if post.projectid == "okavango" %}
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

<ul class="post-list">
{% for post in site.categories.images %}
  {% if post.projectid == "rwenzori" %}
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

### Training material

<ul class="post-list">
{% for post in site.categories.training %}
  {% if post.projectid == "rwenzori" %}
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
