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
* B.S. in Aerospace Engineering, Xi'an Jiao Tong University, 2010
* M.S. in Aerospace Engineering, Shanghai Jiao Tong University, 2013
* Ph.D in Applied and Computational Mathematics, Florida State University, 2021 (expected)

Work experience
======
* May 2020 - Aug 2020: Machine Learning Reseach Intern, Kwai.inc
  * Ads ranking
  * E-commerce ads content understanding (Scene Text Recoginition with deep learning)

* May 2019 - Aug 2019: SDE intern, Weride.ai
  * Designed an intelligent human driver agent which has multiple behavioral intentions
  * Prototyped the application of reinforcement learning algorithm (DP, DQN) to solve lane change problem for Autonomous Vehicle, achieved zero collision out of 1 million episode of lane changes
  
* June 2017 - Aug 2017: Computational Science Summer Student Internship (NSF Mathematics Science Graduate Internship), Lawrence Berkeley National Laboratory
  * Developed code based on AMReX, which is a massively parallel adaptive mesh refinement framework, to solve wave equations in C++ and Fortran
  * Added node-level parallelism with a MPI plus Open MP approach. Improved thread scalability by experimenting the combination of MPI tasks and threads, achieved 1.5x speed up compared with pure MPI approach
  
Skills
======
* Machine Learnin
  * Deep Learning (CNN, RNN)
  * Reinforcement Learning
* CFA

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
