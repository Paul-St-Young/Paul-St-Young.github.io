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
* B.S. in Math and Physics, Denison University, 2014
* Ph.D in Physics, University of Illinois Urbana Champaign, 2020 (expected)

Work experience
======
  
Skills
======
* Quantum Monte Carlo simulation
* Many-body wavefunction analysis
* Programming
  * Fortran
  * Python
  * C++
* Visualization
  * matplotlib3d
  * Unreal engine

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
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* [Algorithm Interest Group][1]

[1]: http://algorithm-interest-group.me/
