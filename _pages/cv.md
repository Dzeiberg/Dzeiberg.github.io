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

* Northeastern University, Boston, MA, 2018 - Present
  * PhD in Computer Science

* University of Michigan Engineering Honors College, Ann Arbor, MI, 2014 - 2018
  * B.S.E in Computer Science Engineering with a minor in statistics
  * Summa Cum Laude

Work experience
======
* January 2019 - Present: Graduate Research Assistant: Northeastern University
  * Developed a deep learning model for class prior estimation for positive-unlabeled data using Tensorflow
  * Researching heterogeneous graph-based models for compound protein interaction prediction using Pytorch

* September 2018 - December 2018: Graduate Research Assistant: Northeastern University
  * Developed a deep sequence-to-sequence model using GRUs that forecasts spatiotemporal data
  * Achieved prediction accuracy on-par with published methods for next hour traffic speed forecasting in the METR-LA dataset
  * Trained model to forecast realistic sequences of human poses using the Human3.6M dataset

* May 2017 - April 2018: Research Assistant: University of Michigan
  * Implemented a model that risk stratifies hospital patients for Acute Respiratory Distress Syndrome
  * Developed a model that beats the current leading method by a significant margin
  * Supervisor: Jenna Wiens

* June - August 2016: Software Defined Core Network Engineering Intern: Comcast
  * Developed a network health dashboard that displays key metrics on Comcast’s service performance and identifies service outages using Python, the Django framework, JavaScript, and JQuery
  * Wrote Python scripts that automate the IP address cleanup workflow, managing millions of IPs

* May - July 2015: Engineering Analysis Intern: Comcast
  * Created visualizations using the D3.js data visualization library that modeled On-Demand data flow
that was used by business operations personnel to make decisions on network scaling
  * Taught myself advanced JavaScript techniques and the fundamentals of data visualization

* July - August 2015: Software Development Intern: Scholly
  * Developed an online database management console that allows team members to update
scholarships and view database metrics, using MySQL, Python, and Django
  * This tool automated Scholly’s database management, improving efficiency across the company

Achievements and Skills
======
* “Most Likely To Have Transformative Scientific Impact” Award - MIDAS Symposium 2017
* Tau Beta Pi Engineering Honor Society
* Proficient in C++, Python, Matlab, Java, MySQL, Node.js, Angular.js, MongoDB, Express.js


Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
<!--   
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
* Currently signed in to 43 different slack teams -->
