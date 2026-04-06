---
layout: page
permalink: /teaching/
title: teaching
description: Materials for courses you taught. Replace this text with your description.
nav: true
nav_order: 3
---


<div class="projects">
  {% assign sorted_projects = site.projects | sort: "importance" %}
  <div class="grid">
    {% for project in sorted_projects %}
      {% include projects.html %}
    {% endfor %}
  </div>
</div>
