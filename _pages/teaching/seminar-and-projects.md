---
layout: page
title: "Seminar and Projects"
description: "Engage in hands-on learning through seminars and projects at MindGarage, the Deep Learning lab at RPTU Kaiserslautern, focused on practical experience in Deep Learning, Computer Vision, and Machine Learning."
date: 2018-10-22 16:54:46
author: Saif Khan
categories:
  - teaching
semester: Summer Semester 2023
status: current
permalink: /teaching/seminar-and-projects/
---

The <a href="https://ags.cs.uni-kl.de/">Augmented Vision department</a> at the RPTU Kaiserslautern-Landau offers an opportunity to work with different faculty members on a variety of master projects (8 CP) and seminars (4 CP) each semester. This also includes projects and seminars from the MindGarage group. The topics we offer are related to the applications of deep learning on computer vision tasks, including but not limited to:

- 3D reconstruction
- 3D scene understanding
- Document analysis
- Floor plan analysis
- Image captioning
- Image classification
- Image generation
- Object detection and segmentation
- Video analysis

You can find proceedings of the projects and seminars from the previous semesters on the [department website](https://ags.cs.uni-kl.de/teaching/current-semester/seminars-projects-and-guided-research). Instructions for registration can also be found there. The topics from our group are listed below.

{% assign projects = site.data.projects | sort: 'year' | reverse %}
{% assign current_year = site.time | date: '%Y' %}
{% assign current_month = site.time | date: '%m' | times: 1 %}
{% if current_semester >= 9 or current_month <= 3 %}
{% assign current_semester = 'WS' %}
{% if current_month <= 3 %}
{% assign semester_year = current_year | minus: 1 | append: "/" %}
{% assign next_year = current_year %}
{% assign semester_year = semester_year | append: next_year %}
{% else %}
{% assign semester_year = current_year %}
{% assign next_year = current_year | plus: 1 %}
{% assign semester_year = semester_year | append: "/" | append: next_year %}
{% endif %}
{% else %}
{% assign current_semester = 'SS' %}
{% assign semester_year = current_year %}
{% endif %}

{% assign current_semester = current_semester | append: " " %}
{% assign current_semester = current_semester | append: semester_year %}

### Topics in {{ current_semester }}

{% for project in projects %}
{% assign project_semester = project.semester | append: " " %}
{% assign project_semester = project_semester | append: project.year %}
{% if project_semester == current_semester %}
- __{{ project.title }}__. _{{ project.authors }}_.
{% endif %}
{% endfor %}

### Past Topics

{% for project in projects %}
{% assign project_semester = project.semester | append: " " %}
{% assign project_semester = project_semester | append: project.year %}
{% if project_semester != current_semester %}
- ({{ project_semester }}) __{{ project.title }}__. _{{ project.authors }}_.
{% endif %}
{% endfor %}

### Prerequisites
Students who want to work on a project or seminar offered by the MindGarage group should have successfully completed the "[Very Deep Learning](/teaching/very-deep-learning/)" course and have a good understanding of deep learning concepts.

If you are interested in working with us on a project or seminar, please [contact us](/contact/).