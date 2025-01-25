---
layout: splash
entries_layout: grid
title: Projects
permalink: /projects/
---

# My Data Science & Analytics Projects
{: #projects-header}

Welcome to my projects page! Below are some of the exciting data science and data analytics projects I have worked on. Click on each project to learn more.
{: .text-center}

---

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
