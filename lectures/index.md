---
layout: resume
title: Lectures
excerpt: "Archive of lectures"
search_omit: true
share: true
---

Lectures that I created and delivered during my early years at the Royal Institute of Technology (KTH) (1989-1998) and at Uppsala University (1998-2000) are only available in analog formats. Only lectures created while working as a senior lecturer in Geoinformatics at KTH (2005-2008) are available in digital format. Below are most of my lectures from that period, divided between the different courses I was involved in.

# GIS Grundkurs (1n1651), KTH, Stockholm, Sweden.

The course gives an introduction to Geographic Information Systems (GIS), CAD, database technology and reference systems

I was responsible for the GIS part of this course between 2006 and 2008.

## Course content

Databases: How to design and use databases. Database structure, query languages, different types of database structures.

Reference systems: Description of some reference surfaces, how reference systems can be established, examples of local and global existing systems. Acquisition of data.

Geographic Information Technology: Areas of application. Data sources, quality of data, data access etc.

Digitising and scanning. Data structure and storage. Searches and analyses, visualisation.

CAD: Principles of graphic representation, drawing technique, norms.

## My lectures

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

# GIS for the Built Environment (1n1654), KTH, Stockholm, Sweden

A course on GIS techniques and applications, with various case studies related to surveying, urban planning, land management and traffic planning.

I was responsible for this course between 2006 and 2008.

## Course content

+ Basic GIS architecture
+ Spatial data models and structures
+ Data sources
+ Database concepts
+ Vector data operations
+ Raster data operations
+ Spatial query
+ Spatial analysis
+ Network analysis

## My lectures

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

# Geovisualisation (ag2412), KTH, Stockholm, Sweden

Advanced cartography and visualisation, symbolization of analogue and digital maps, graphical signal system, 3D graphics, VRML. Interactive and dynamic web publishing of spatial data. Scripting and automation of map layout and symbolization.

I was responsible for this course between 2006 and 2008.

## Course content

- Map symbols
- Visual variables: spacing, size, orientation, shape, arrangement, height, hue, value, saturation.
- Data classification
- Topographic and thematic map design and symbolization
- Map design for presentation, synthesis, analysis and exploration of spatial data
- Exploratory data analysis, graphical data analysis techniques
- 2D, 2.5D, and 3D data and their representation
- Temporal data and their representation

## My lectures

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
