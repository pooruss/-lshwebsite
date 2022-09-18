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
* B.S. in Tianjin University, 2022

Work experience
======
* Aug. - Oct. 2021: R & D Intern, Tianhu Product Center Department
  * Beijing Zhongke Wenge Tech. Ltd.
  * Duties included: 
      * Undertook a real-time protection project of residents' license plate privacy, applied the project achievement into practice and awarded the Third Prize of practical training in the company;
      * Data augmentation: Enhanced data diversity by rotating and flipping the license plate, improved the models’ robustness.
      * Model building and training: Adopted yoloV5 one-stage algorithm to reproduce the relevant model algorithm based on Pytorch framework in the context of programming of Python;
  * Supervisor: Xianqin Ma

* Dec. 2021 - April. 2022: R & D Intern, NLP Department
  * Beijing Baidu Network Technology Co., Ltd.
  * Duties included: 
      * Supported first result optimization of search engine; Leveraged Python to mine hard negatives from user query log, with the help of algorithms such as levenshtein distance, term weight calculation based on LSTM;
      * Applied hard negative data to model training to improve semantic relevance ranking models' accuracy based on ERNIE;
      * Assisted in the application of search question and answer technology in industrial projects, fine tuned models with tens of thousands domain data and distilled models using tens of millions of data in the framework of paddle, distilled a small model with only 2-layer transformer encoder from the large model of 12-layer transformer encode to produce a lightweight model with satisfactory efficiency and effect.
  * Supervisor: Yuchen Ding
  
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
* Currently signed in to 43 different slack teams
