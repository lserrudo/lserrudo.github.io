---
layout: page
permalink: /teaching/
title: teaching
description: Materials for courses you taught. Replace this text with your description.
nav: true
nav_order: 3
display_categories: [teaching]
---


<div class="projects">
  {% assign teaching_projects = site.projects | where: "category", "teaching" | sort: "importance" %}
  <div class="grid">
    {% for project in teaching_projects %}
      {% include projects.html %}
    {% endfor %}
  </div>
</div>
