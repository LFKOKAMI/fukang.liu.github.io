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
* B.S.  in Information Security, Donghua University, Shanghai, China, 2017
* Ph.D. in Software Engineering, East China Normal University, Shanghai, China, 2021

Work experience
======
* Apr. 2020 - Mar. 2022: Specially Appointed Researcher
  * University of Hyogo, Hyogo, Japan
  * Duties included: Research on symmetric-key cryptanalysis and design
  * Supervisor: Takanori Isobe

* Apr. 2022 - Mar. 2023: Specially Appointed Lecturer
  * University of Hyogo, Hyogo, Japan
  * Duties included: Research on symmetric-key cryptanalysis and design

* Apr. 2023 - Now: Assistant Professor
  * Tokyo Institue of Technology, Tokyo, Japan
  * Duties included: Research, co-supervising and teaching
  
Awards
======
* 2022, Fast Software Encryption 2022 (FSE 2022) best paper award
* 2022, 第七回「辻井重男セキュリティ論文賞」


Publications
======
  <ul>{% for post in site.publications reversed%}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed%}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed%}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service
======
* FSE 2024, program committee
* ASIACRYPT 2023, program committee
* FSE 2023, general chair in Kobe
* Indocrypt 2023/2022, Program committe
