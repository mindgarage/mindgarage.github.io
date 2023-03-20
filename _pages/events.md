---
layout: page2
title: Events
permalink: /events/
---

We organize a variety of events, such as workshops, lectures, and conferences where we present our research and discuss the latest developments in deep learning. You can learn more about them here.

{% assign events = site.pages | where: "categories", "event" %}
{% for item in events %}
- [{{ item.title }}]({{ item.url }})
{% endfor %}
