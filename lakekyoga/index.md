---
layout: resume
title: Lake Kyoga, Uganda
excerpt: "An archive of Lake Kyoga publications"
search_omit: true
share: true

---

Kyoga is a shallow lake north of Lake Victoria in Uganda. In 2003 I raised funding for a 2 year project on "Integrated management of Lake Kyoga natural resources". Project partners included Uppsala University (Sweden), and Fisheries Resoruces Research Institute (FIRRI) Department of Water Development in Uganda. The project was financed by the Swedish International Development Cooperation Agency (SIDA).

### Conference Proceedings

<ul class="post-list">
{% for post in site.categories.conference %}
  {% if post.projectid == "kyoga" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}  
</ul>

### Presentations

<ul class="post-list">
{% for post in site.categories.talk %}
  {% if post.projectid == "kyoga" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}  
</ul>

### Posters

<ul class="post-list">
{% for post in site.categories.poster %}
  {% if post.projectid == "kyoga" %}
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

Not yet available

<ul class="post-list">
{% for post in site.categories.movie %}
  {% if post.projectid == "kyoga" %}
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
  {% if post.projectid == "kyoga" %}
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
