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
* May 2020 - Aug 2020: Machine Learning Research Intern, Kwai.inc
  * Ads ranking on video-sharing app with 200 million DAU
  * E-commerce ads content understanding (image Scene Text Understanding and multimodal learning)

* May 2019 - Aug 2019: SDE intern, Weride.ai
  * Designed an intelligent human driver agent which has multiple behavioral intentions
  * Prototyped the application of reinforcement learning algorithm (DP, DQN) to solve lane change problem for 
  Autonomous Vehicle, achieved zero collision out of 1 million episode of lane changes
  
* June 2017 - Aug 2017: Computational Science Summer Student Internship (NSF Mathematics Science Graduate Internship),
 Lawrence Berkeley National Laboratory
  * Developed code based on AMReX, which is a massively parallel adaptive mesh refinement framework, to solve wave 
  equations in C++ and Fortran
  * Added node-level parallelism with a MPI plus Open MP approach. Improved thread scalability by experimenting the 
  combination of MPI tasks and threads, achieved 1.5x speed up compared with pure MPI approach
 
Research experience
======
* Sep 2017 - Present: Research Assistant, Florida State University
  * Extracted and labeled 120000 vehicle trajectories with a total driven distance of 45000km
  * Trained Logistic Regression/Support Vector Machine/LSTM models to predict human intentions by learning from human 
  driving dataset. Achieved 87.8% accuracy in predicting cooperative/adversarial behavior in lane change
  * Trained a Compact Support Neural Network (CSNN) to quantify uncertainty and detect long-tail rare events. CSNN 
  obtained similar accuracy in classifying in-distribution samples compared with normal neuron based network, and 
  achieved AUC of 0.99 in detecting out-of-distribution samples
 
Skills
======
* Machine Learnin (Pytorch, Tensorflow)
  * Deep Learning (CNN, RNN) 
  * Reinforcement Learning
* CFA
* Programming (C++, Python, SQL)

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
* Fellows society at Florida State University
