---
title: Projects
nav:
  order: 2
  tooltip: Research projects, Papers and Reviews
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

This page showcases our current and past research projects. We strive to create high-quality resources: clearly written, robustly built and tested, well-documented, easy to use, accessible, and as practically effective as possible.

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Current

{% include list.html component="card" data="projects" filter="group == 'current'" %}

{% include section.html %}

## Past

{% include list.html component="card" data="projects" filter="!group" style="small" %}
