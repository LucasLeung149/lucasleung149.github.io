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
* D.Phil. (PhD) in Theoretical Physics, University of Oxford, 2026 (expected)
* M.Math. in Part III Mathematical Tripos, University of Cambridge, 2022
* B.A. in Natural Sciences (Physics), University of Cambridge, 2021

Work experience
======
*  2022 - now : Tutor and class tutor at Oxford
  * University of Oxford
  * Duties includes: Teaching undergraduate students
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

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
  
Service and leadership
======
* Currently signed in to 43 different slack teams
