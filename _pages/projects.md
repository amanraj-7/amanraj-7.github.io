---
layout: page
title: projects
permalink: /projects/
description: Research and policy projects
nav: true
nav_order: 3
display_categories: [dissertation, lab research, policy research]
horizontal: false
---

<!-- pages/projects.md -->
<div class="post">
{% for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  {% assign categorized_projects = site.projects | where: "category", category %}
  {% assign sorted_projects = categorized_projects | sort: "importance" %}
  <ul class="post-list">
    {% for project in sorted_projects %}
      <li>
        {% if project.img %}
          <div class="row">
            <div class="col-sm-9">
        {% endif %}
        <h3>
          <a class="post-title" style="font-weight: 700;" href="{{ project.url | relative_url }}">{{ project.title }}</a>
        </h3>
        <p>{{ project.description }}</p>
        {% if project.img %}
          </div>
          <div class="col-sm-3">
            <img class="card-img" src="{{ project.img | relative_url }}" style="object-fit: cover; height: 90%" alt="{{ project.title }}">
          </div>
          </div>
        {% endif %}
      </li>
    {% endfor %}
  </ul>
{% endfor %}
</div>
