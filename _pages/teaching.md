---
layout: page2
title: Teaching and Supervision
permalink: /teaching/
---

We offer a variety of courses and seminars at the [RPTU Kaiserslautern-Landau](https://rptu.de/). The courses are offered in the [Department of Computer Science](https://cs.rptu.de/) and are related to the applications of deep learning on computer vision tasks. The courses are offered in English.

<div class="col-lg-12">
<div class="mdc-layout-grid">
    <div class="mdc-layout-grid__inner">
    {% assign current_courses = site.pages | where: "categories", "teaching" | where: "status", "current" %}
    {% for item in current_courses %}
    <div class="mdc-card mdc-card--outlined mdc-layout-grid__cell mdc-layout-grid__cell--span-3-desktop mdc-layout-grid__cell--span-4-tablet mdc-layout-grid__cell--span-6-phone">
        <a href="{{ item.url }}" class="mdc-card__content" style="background-color: var(--mdc-theme-surface)">
        <p style="color: var(--mdc-theme-on-surface); text-align: center;">{{ item.title }}</p>
        </a>
    </div>
    {% endfor %}
    </div>
</div>
</div>