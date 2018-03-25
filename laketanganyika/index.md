---
layout: publication
title: Lake Tanganyika Regional Integrated Management Project.
excerpt: "An archive of Lake Tanganyika publications"
search_omit: true
share: true

---
A United Nations Development Programme (UNDP) / Global Environmental Facility (GEF) project covering the Lake Tanganyika riparian countries, Burundi, the Democratic Republic of Congo, Tanzania and Zambia.

Within the project I organized and led training workshops in Kenya, Tanzania, Zambia and the Democratic Republic of Congo (DRC). I also held the training modules on spatial data analysis and land degradation in each project country.

### Presentations

<ul class="post-list">
{% for post in site.categories.talk %}
  {% if post.projectid == "tanganyika" %}
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
  {% if post.projectid == "tanganyika" %}
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
{% for post in site.categories.popular %}
  {% if post.projectid == "tanganyika" %}
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
  {% if post.projectid == "tanganyika" %}
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
