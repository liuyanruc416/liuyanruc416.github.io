---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!--
============================================================================
 TODO (Yanru):
 1. Put your CV PDF in the  files/  folder, named exactly  cv.pdf
    (path will be  https://liuyanruc416.github.io/files/cv.pdf ).
 2. Fill in the short summary below (or delete the sections you do not
    want and keep only the PDF download link).
 Each "======" line under a heading turns it into a section divider.
============================================================================
-->

[**Download my full CV (PDF)**](/files/cv.pdf){: .btn .btn--primary}

Education
======
* TODO: Ph.D. in Communication / Advertising / Public Relations, *University*, *year (expected)*
* TODO: M.A. in *Field*, *University*, *year*
* TODO: B.A. in *Field*, *University*, *year*

Research interests
======
* TODO: interest one
* TODO: interest two

Selected publications
======
<!-- This list is generated automatically from your _publications files. -->
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
<!-- Generated automatically from your _talks files. -->
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
<!-- Generated automatically from your _teaching files. -->
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
