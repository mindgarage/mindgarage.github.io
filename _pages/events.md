---
layout: page
title: Workshops and Events
permalink: /events/
---

We organize a variety of events, such as workshops, lectures, and conferences where we present our research and discuss the latest developments in deep learning. You can learn more about them here.

{% assign events = site.pages | where: "categories", "event" %}
{% for item in events %}
- [{{ item.title }}]({{ item.url }})
{% endfor %}

In addition, we also organize social events where we meet up for a drink or a meal. Below is our complete event calendar.

{% assign sorted_events = site.categories['event'] | sort: 'estart' | reverse %}
{% for item in sorted_events %}
- {{ item.estart | date: "%Y-%m-%d" }}: [{{ item.title }}]({{ item.url | prepend: site.baseurl }})
{% endfor %}