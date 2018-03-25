---
layout: publication
title: West African Drylands Project
excerpt: "An archive of Lake sahel publications"
search_omit: true
share: true

---

An Ecosystem Approach to Restoring West African Drylands and Improving Livelihoods through Agroforestry-based Land Management Interventions. A United Nations Environment Programme (UNEP) project conducted in partnership with the World Agroforestry Centre (ICRAF), the Centre for Environmental Policy of the University of Florida, and the Governments of Burkina Faso, Mali, Mauritania, Niger and Senegal. Project funded by the Government of Norway.

My part in the project included development of land degradation monitoring from time series of satellite images, general landscape mapping and historical climate change analysis.

### Journal articles

<ul class="post-list">
{% for post in site.categories.journal %}
  {% if post.projectid == "sahel" %}
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

### Atlas

<ul class="post-list">
{% for post in site.categories.atlas %}
  {% if post.projectid == "sahel" %}
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

### Reports

<ul class="post-list">
{% for post in site.categories.report %}
  {% if post.projectid == "sahel" %}
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

### Presentations

<ul class="post-list">
{% for post in site.categories.talk %}
  {% if post.projectid == "sahel" %}
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

<ul class="post-list">
{% for post in site.categories.training %}
  {% if post.projectid == "sahel" %}
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
  {% if post.projectid == "sahel" %}
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
  {% if post.projectid == "sahel" %}
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
