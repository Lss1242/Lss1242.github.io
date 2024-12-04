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
* B.S. in Mathematics, University of Warwick, 2017-2020
* M.S. in Pure Mathematics, Imperial College London, 2020-2021
  * Master Thesis:  An Overview on Random Matrix Theory
* Ph.D in Computer Science, University of Birmingham, 2021-2025 (expected)

Work experience
======
* Summer 2020: Data Analyst Intern
  * Tencent Technology, Shenzhen, China
  * Duties: A 10-weeks summer intern on data analysis. A business and data analyst internship on supporting Tencent Advertising Market Services in particular IAA ( In-App Advertising) division. Analyse data from Ads in Games by using Excel and Python and update data for weekly reports of IAA. Also use Pandas and Numpy to simplify Excel computation.
  <!-- * Supervisor: Dr. Chris Williams. -->

* Summer 2020: Research Assistant
  * University of Warwick, Coventry, United Kingdom
  * Duties: A 10-weeks funded summer project on number theory, which is supervised by Dr. Chris Williams. The project mainly focuses on rational points on elliptic curves, which is an important object in number theory. It is also important in some modern encryption. During the project, I learn the theory of elliptic curves and use some elementary algebraic geometry to solve number theoretic questions. Meanwhile, I am trying to learn Sage software to do some complicated calculation, which is based on Python Programmimg.
  * Supervisor: Dr. Chris Williams.


* Summer 2019: Research Assistant
  * University of Warwick, Coventry, United Kingdom
  * Duties: A 10-week funded research program on stability and sound in ducted flow, supervised by Dr Ed Brambley. The project mainly studied the instability problem by using mathematical analysis.
  * Supervisor: Dr Ed Brambley


Publications (authors are listed in alphabetical order in theory papers, following the tradition of theory community)
======
  <ul>{% assign sorted_publications = site.publications | sort: 'date' | reverse %}
      {% for post in sorted_publications %}
      {% include archive-single-cv.html %}
    {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  

