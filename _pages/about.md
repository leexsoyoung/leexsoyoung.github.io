---
permalink: /
title: "Soyoung Lee"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
{% include base_path %}

Education
======
* Ph.D Student in Graduate School of Information Security, KAIST, MAR.2022 - Now 
* M.S. in Graduate School of Information Security, KAIST, Feb.2022
* B.S. in School of Computing, KAIST, Feb.2020


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!--
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
-->  


Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Work experience
======
* Winter 2018: Internship Program
  * Inc. H2K
  * Web developer
