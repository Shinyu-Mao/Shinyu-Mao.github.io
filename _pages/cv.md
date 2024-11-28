---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D, The University of Queensland, 2025 (expected)
* M.S. in Data Science, The University of Queensland, 2021
* B.A. in English Literature, Shanghai Ocean University, 2019
* B.E. in Mechanical Engineering, Shanghai Ocean University, 2019

Work experience
======
* **Visiting Scholar**
  * Leipzig University
  * Host: Dr. Harrisen Scells, Professor Martin Potthast

* **Research Assistant**
  * The University of Queensland
  * Participated in Preserving the Privacy and Cybersecurity of Home Energy Data
  * Supervisor: Dr. Yanjun Zhang

* **Teaching Assistant**
  * The University of Queensland
  * Courses: DATA7001, INFS7410
  * Supervisor: Dr. Joel MacKenzie, Professor Guido Zuccon

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
## Awards
<ul>{% for post in site.awards %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
