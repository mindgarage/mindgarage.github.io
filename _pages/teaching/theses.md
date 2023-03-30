---
layout: page
title: "Master Theses"
description: "Dive into a world of research opportunities with MindGarage's theses topics in Deep Learning, Computer Vision, and Machine Learning at RPTU Kaiserslautern. Collaborate with leading experts and contribute to the future of AI."
date: 2018-10-22 16:54:46
author: Saif Khan
categories:
  - teaching
semester: Summer Semester 2023
status: current
permalink: /teaching/theses/
---

If you are interested in one of the announced topics, please send your application, including your transcript. If you are interested in a different topic, have own ideas, or wish more information concerning one of the running these, please [write to us](/contact/).

### Current Theses

There are no ongoing theses at the moment or the information is not available. You are welcome to [contact us](/contact/) for more information or to discuss your own ideas.

### Completed Theses

Here is a list of master's theses that have been completed in the past:

{% assign sorted_theses = site.data.theses | sort: 'date' | reverse %}
{% for thesis in sorted_theses %}
{% assign url = thesis.url | prepend: site.baseurl %}
- ({{ thesis.date }}) [__{{ thesis.title }}__]({{ url }}). _{{ thesis.author }}_. <br>
{% endfor %}