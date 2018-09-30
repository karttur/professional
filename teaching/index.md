---
layout: resume
title: Teaching material
excerpt: "An archive of teaching material"
search_omit: true
share: true
---

I do not really like powerpoint (or keynote as I am a mac user). I prefer blackboard (the old type) both as a teacher and when in the audience.

## Lectures

[link to page with lectures as pdf documents](../lectures)

[Link to old page with lectures](http://www.karttur.com/private/teaching/index.htm)

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
  {% if post.pageurl %}
    <a href="{{ post.pageurl }}">
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

## Training projects

[link to page with training projects as pdf documents](../trainingproj)

[Link to old page with training documents](http://www.karttur.com/private/teaching/index.htm)

## Course evaluations

[Link to various course evaluations from KTH and UU](../courseevaluations).

## Course compendiums

[Link to various course compendiums from KTH and UU](../coursecompendiums).


## Course excursions

[Link to international excursions that I arranged or assisted in arranging as part of my teaching at KTH ](../courseexcursions).

## Student course reports

[Link to student course reports from KTH ](../courseprojects).

## Didactic approach

When I first started my doctoral studies I took a great interest in educational training approaches and took part in seminars and discussions, which led me to convert my courses to use Problem Based Learning (PBL) and triple examinations (see below). But I have no formal university in educational training, only shorter courses as part of my military training and as a youth-leader.

When I started my PhD studies I had four years experience as a consultant, and I came to emphasize the application of real world problems in my teaching. Already from the start (1988) I got the responsibility for a 10 week (15 credits) course for the last (4th) year students at the school of surveying at KTH. I took an interested in didactic approaches and participated in seminars and contacted universities that had adopted Problem Based Learning (PBL). Parallel to the course I gave, the students followed a course in Geographic Information Systems (GIS). While my course used traditional analogue data and approaches, the GIS course used digital data but without considering any real problems. I hence created an integrated course in 1992 (30 credits), for which I also became responsible. In parenthesis, this is how I learnt GIS and remote sensing. The integrated course used real world data and problems stemming out of my course, but data and approaches from the GIS course. Inspired by PBL I created projects that had to be reported both as articles and orally. I also changed the examination form to a triple jump examination, where the examination is divided into three parts: 1) strategy formulation, 2) solution structuring and 3) re-evaluation. In the first part the students are given a (written) problem for which they must suggest a strategy for solving (1 hour). During six hours they then seek information that must be structured and synthesized to show the feasibility of their strategy. A last hour is given for re-evaluating their approach. All parts are to be reported in writing and must be handed in at set times. The students knew already from the start of the course that this was to be the type of exam.

The integrated 20 week course was later used by KTH to start the schools first international Masters program, in Environmental Engineering (1993). When this program was set up, my course constituted half the course part. The following year, a second international master course, in Sustainable Infrastructure (1994), was set up. Again my course was used as the vehicle, constituting half of the course part. The development of the course and its benefits and problems is reported in Gumbricht (1995) and Gumbricht and McCarthy (1996). The two programs were merged into a single Masters program on Environmental Engineering and Sustainable Infrastructure (EESI), still offered at KTH.

Also at Uppsala University (department of Earth Sciences) I introduced PBL, and changed the GIS courses to thematically revolve around real world problems related to parallel courses in thematic Earth Science fields, for example in climatology, sedimentology and geophysics. Uppsala University also offered GIS as distance learning, and all courses were at basic level. I had to abandon the triple jump examination, and revert to more ordinary examination forms. I, however, kept the reporting style being both in the form of articles and oral presentations.

During my second session at KTH (2005 to 2009) I taught geoinformatics as a subject on its own (not as an applied tool in other fields as I had done before). I still adopted a PBL style of learning, but this time by giving the students options to reach higher grades by developing system solutions
