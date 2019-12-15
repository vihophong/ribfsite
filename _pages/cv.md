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
* B.S. in VNU University of Science, 2011
* M.S. in VNU University of Science, 2014
* Ph.D in VNU University of Science, 2019 (expected)

Work experience
======
* 2011-2014: Research and Teaching Assistant
  * VNU University of Science
  * Duties included: Operating the University Tandem Pelletron Accelerator.
  * Supervisor: Dr. Nguyen The Nghia, Dr. Le Hong Khiem

* 2014 2018: Student internship (IPA)
  * RIKEN Nishina center
  * Duties included: Setting up three detector systems: BRIKEN, EURICA, NiGIRI. Performing data analysis.
  * Supervisor: Dr. Shunji Nishimura, Dr. Le Hong Khiem
  
Skills
======

* C++, PHP, HTML, Javascript, Visual Basic, Swift programing
* Analysis and simulation toolkits: CERN ROOT, GEANT4
* DAQ system

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Research
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
