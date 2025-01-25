---
layout: page
entries_layout: grid
title: My Projects
permalink: /projects/
intro: 
  - excerpt: 'Welcome to my projects page! Below are some of the exciting data science and data analytics projects I have worked on. Click on each project to learn more.'
---

{% include feature_row id="intro" type="center" %}

# My Data Science & Analytics Projects

Welcome to my projects page! Below are some of the exciting data science and data analytics projects I have worked on. Click on each project to learn more.

<div class="projects-grid">
  {% for project in site.projects %}
    <div class="project-item">
      <a href="{{ project.url }}">
        <img src="{{ project.teaser_image }}" alt="{{ project.title }}" class="project-teaser-img" />
        <h3>{{ project.title }}</h3>
      </a>
    </div>
  {% endfor %}
</div>
