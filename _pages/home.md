---
layout: single
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /home/
  - /home.html
---

{% include base_path %}

<p class="home-intro">
I am an <strong>Assistant Professor</strong> in the Department of Computing Sciences at
<strong>Bocconi University</strong> and a member of the Bocconi Institute for Data Science and
Analytics (BIDSA). My research combines <strong>Computational Intelligence</strong> and
<strong>Deep Learning</strong> with <strong>High-Performance Computing</strong> to tackle complex
problems in biology and medicine — from single-cell omics and systems biology to biomedical image
analysis and precision medicine. I am always open to interdisciplinary collaborations.
</p>

<div class="focus-grid">
  <div class="focus-card">
    <div class="focus-card__icon"><i class="fa-solid fa-brain" aria-hidden="true"></i></div>
    <h3>Computational Intelligence &amp; AI</h3>
    <p>Evolutionary Computation, Swarm Intelligence, Fuzzy Logic and Deep Learning for optimization and modelling.</p>
  </div>
  <div class="focus-card">
    <div class="focus-card__icon"><i class="fa-solid fa-dna" aria-hidden="true"></i></div>
    <h3>Computational Biology &amp; Bioinformatics</h3>
    <p>Single-cell omics, systems biology, genome analysis and multi-omics data integration.</p>
  </div>
  <div class="focus-card">
    <div class="focus-card__icon"><i class="fa-solid fa-microchip" aria-hidden="true"></i></div>
    <h3>High-Performance Computing</h3>
    <p>GPU-accelerated methods to scale up the simulation and analysis of large biomedical problems.</p>
  </div>
</div>

<section class="home-section">
  <h2 class="home-section__title" id="grants">Grants</h2><hr />
  <div class="grant-grid">
    {% for grant in site.data.grants %}
      <div class="project-card">
        <div class="project-card__icon"><i class="fa-solid {{ grant.icon | default: 'fa-award' }}" aria-hidden="true"></i></div>
        <p class="project-card__title">{{ grant.title }}</p>
        {% if grant.subtitle %}<span class="project-card__subtitle">{{ grant.subtitle }}</span>{% endif %}
        <p class="project-card__desc">{{ grant.description }}</p>
      </div>
    {% endfor %}
  </div>
</section>

<section class="home-section">
  <h2 class="home-section__title" id="projects">Projects &amp; Tools</h2><hr />
  <div class="project-grid project-grid--tools">
    {% for project in site.data.projects %}
      {% if project.url contains "gitlab" %}{% assign brand = "fa-gitlab" %}{% else %}{% assign brand = "fa-github" %}{% endif %}
      <a class="project-card" href="{{ project.url }}">
        <div class="project-card__icon"><i class="fa-brands {{ brand }}" aria-hidden="true"></i></div>
        <p class="project-card__title">{{ project.title }}</p>
        <p class="project-card__desc">{{ project.description }}</p>
      </a>
    {% endfor %}
  </div>
</section>

<section class="home-section">
  <h2 class="home-section__title" id="news">Latest News</h2><hr />
  <ul class="news-list">
    {% assign sorted_news = site.data.news | sort: "date" | reverse %}
    {% for item in sorted_news %}
      <li class="news-item">
        <div class="news-item__meta">
          <span class="news-item__date">{{ item.date | date: "%d %b %Y" }}</span>
          {% if item.tag %}<span class="news-item__tag">{{ item.tag }}</span>{% endif %}
        </div>
        <h3 class="news-item__title">
          {% if item.url %}
            {% if item.url contains "://" or item.url contains "mailto" %}{% assign n_url = item.url %}{% else %}{% assign n_url = item.url | prepend: base_path %}{% endif %}
            <a href="{{ n_url }}">{{ item.title }}</a>
          {% else %}
            {{ item.title }}
          {% endif %}
        </h3>
        {% if item.excerpt %}<p class="news-item__excerpt">{{ item.excerpt }}</p>{% endif %}
      </li>
    {% endfor %}
  </ul>
</section>
