---
title: 最新项目
nav:
  order: 3
  tooltip: Latest projects
---

# {% include icon.html icon="fa-solid fa-wrench" %}最新项目

（最新项目简介）

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}


{% include list.html component="card" data="projects" filters="group: featured" %}

{% include section.html %}

## 更多研究项目

{% include list.html component="card" data="projects" filters="group: " style="small" %}
