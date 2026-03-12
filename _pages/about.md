---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
{% include base_path %}



Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-pub.html %}
  {% endfor %}</ul>

---

Education
======
* Ph.D Student in Graduate School of Information Security, KAIST, MAR.2022 - Now
* M.S. in Graduate School of Information Security, KAIST, Feb.2022
* B.S. in School of Computing, KAIST, Feb.2020

---

Teaching
======
{% assign ta_posts = site.teaching | where: "type", "Teaching Assistant" %}{% if ta_posts.size > 0 %}<p style="margin-bottom: 2px;"><strong>Teaching Assistant</strong></p><ul style="margin-top: 0;">{% for post in ta_posts %}<li>{{ post.course_id }} {{ post.title }}: {{ post.terms }}</li>{% endfor %}</ul>{% endif %}{% assign tutor_posts = site.teaching | where: "type", "Tutor" %}{% if tutor_posts.size > 0 %}<p style="margin-bottom: 2px;"><strong>Tutor</strong></p><ul style="margin-top: 0;">{% for post in tutor_posts %}<li>{{ post.course_id }} {{ post.title }}: {{ post.terms }}</li>{% endfor %}</ul>{% endif %}

---

Academic Service
======

<p style="margin-bottom: 2px;"><strong>Program Committee</strong></p>{% assign pc_items = site.service | where: "type", "Program Committee" %}<ul style="margin-top: 0;">{% for item in pc_items %}<li>{{ item.venue }}, {{ item.year }}</li>{% endfor %}</ul>

---

Work experience
======
* Winter 2018: Internship Program
  * Inc. H2K
  * Web developer
