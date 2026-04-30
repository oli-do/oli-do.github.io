---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* PhD in Latin Philology, 2029 (expected)
* First State Examination for Teaching at Gymnasien (Grammar Schools) in Latin, English and Educational Sciences, 2025

Work experience
======
* <b>June 2026 (expected): Scientific Assistant</b>
  * University of Heidelberg
  * Supervisor: Professor Dr. Holger Essler 

* <b>January 2026 - April 2026: Self-employed work</b>
  * Customer: Dr. Saverio Dalpedri (University of Würzburg)
  * Duties included: Encoding magical papyri

* <b>January 2025 - December 2025: Scientific Assistant</b>
  * University of Würzburg
  * Duties included: Developing a parser for TEI-XML, developing an issue finder for papyri.info
  * Supervisor: Dr. Holger Essler

* <b>June 2024 - November 2024: Student Assistant</b>
  * University of Heidelberg
  * Duties included: Developing text-based image extraction for eScriptorium
  * Supervisor: Dr. Rodney Ast

* <b>July 2019 - February 2024: Student Assistant</b>
  * University of Würzburg
  * Duties included: Encoding papyrus texts, developing Python scripts, AI training
  * Supervisor: Dr. Holger Essler
  
Skills
======
* <b>Modern Languages</b>
  * German (mother tongue)
  * English (fluent, C1-C2)
  * Spanish (basic, A1-A2)
* <b>Ancient Languages</b>
  * Latin (State Examination)
  * Ancient Greek (Graecum)
* <b>IT</b>
  * Python (very good)
  * VB.NET (good)
  * Java (basic knowledge)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
