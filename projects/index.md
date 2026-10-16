---
title: Projects
nav:
  order: 2
  tooltip: Funded research projects
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

Our research is supported by 13 funded projects (about $2.0M in total) from the National Science Foundation, the Department of Defense, Sony, the California Education Learning Lab, the CSU system and SF State.

{% include tags.html tags="in progress, completed, Efficient AI, Neural-Machine Interfaces, Intelligent Sensing, AI for Education" %}

{% include search-info.html %}

{% include section.html %}

## In Progress

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## Completed

{% include list.html component="card" data="projects" filter="!group" style="small" %}
