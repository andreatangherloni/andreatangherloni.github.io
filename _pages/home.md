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

<style>
.hp-intro{font-size:1.05em;line-height:1.65;margin-bottom:1.75em;text-align:left;}
.hp-section{margin:2.25em 0;}
.hp-section h2{margin-bottom:.2em;}
.hp-section h2 + hr{margin-top:0;margin-bottom:1.1em;}

.hp-grid{display:grid;gap:1em;}
.hp-grid--3{grid-template-columns:repeat(auto-fit,minmax(230px,1fr));}
.hp-grid--tools{grid-template-columns:repeat(auto-fill,minmax(175px,1fr));}

.hp-card{
  display:flex;flex-direction:column;height:100%;
  padding:1.25em;text-align:left;color:inherit;text-decoration:none;
  background:var(--global-bg-color);
  border:1px solid var(--global-border-color);
  border-radius:8px;
  transition:transform .18s ease, box-shadow .18s ease, border-color .18s ease;
}
a.hp-card:hover{
  transform:translateY(-4px);
  box-shadow:0 10px 24px rgba(0,0,0,.13);
  border-color:var(--global-link-color);
}
a.hp-card:hover .hp-card__icon{transform:scale(1.06);background:var(--global-link-color);color:#fff;}
/* underline only the title on hover, never the description */
a.hp-card, a.hp-card:hover, a.hp-card:focus{text-decoration:none;}
.hp-card__desc, .hp-card__sub{text-decoration:none;}
a.hp-card:hover .hp-card__title{text-decoration:underline;}

.hp-card__icon{
  display:inline-flex;align-items:center;justify-content:center;
  width:46px;height:46px;margin-bottom:.7em;border-radius:12px;
  font-size:1.25rem;color:var(--global-link-color);
  background:rgba(47,127,147,.12);
  transition:transform .18s ease, background .18s ease, color .18s ease;
}
.hp-card__sub{
  font-size:.7rem;font-weight:700;text-transform:uppercase;letter-spacing:.6px;
  color:var(--global-link-color);margin-bottom:.35em;
}
.hp-card__title{margin:0 0 .35em;font-size:1.02em;font-weight:700;line-height:1.3;text-align:left;}
.hp-card__desc{margin:0;font-size:.86em;line-height:1.5;color:var(--global-text-color-light);text-align:left;hyphens:none;}
.hp-card--tool .hp-card__desc{font-size:.82em;}

@media (max-width:600px){
  .hp-grid--tools{grid-template-columns:repeat(auto-fill,minmax(140px,1fr));}
}
</style>

<p class="hp-intro">
I am an <strong>Assistant Professor</strong> in the Department of Computing Sciences at
<strong>Bocconi University</strong> and a member of the Bocconi Institute for Data Science and
Analytics (BIDSA). My research combines <strong>Computational Intelligence</strong> and
<strong>Deep Learning</strong> with <strong>High-Performance Computing</strong> to tackle complex
problems in <strong>biology and medicine</strong>, from single-cell omics and systems biology to biomedical image
analysis and precision medicine. I am always open to interdisciplinary collaborations.
I am also a member of the <a href="https://cis.ieee.org/activities/technical-activities/bioinformatics-and-bioengineering-technical-committee?view=article&amp;id=137:bioinformatics-and-bioinformatics-members&amp;catid=30:technical-committees">IEEE CIS Bioinformatics and Bioengineering Technical Committee (BBTC)</a>.
</p>

<div class="hp-grid hp-grid--3">
  <div class="hp-card">
    <div class="hp-card__icon"><i class="fa-solid fa-brain" aria-hidden="true"></i></div>
    <p class="hp-card__title">Computational Intelligence &amp; AI</p>
    <p class="hp-card__desc">Evolutionary Computation, Swarm Intelligence, Fuzzy Logic and Deep Learning for optimization and modelling.</p>
  </div>
  <div class="hp-card">
    <div class="hp-card__icon"><i class="fa-solid fa-dna" aria-hidden="true"></i></div>
    <p class="hp-card__title">Computational Biology &amp; Bioinformatics</p>
    <p class="hp-card__desc">Single-cell omics, systems biology, genome analysis and multi-omics data integration.</p>
  </div>
  <div class="hp-card">
    <div class="hp-card__icon"><i class="fa-solid fa-microchip" aria-hidden="true"></i></div>
    <p class="hp-card__title">High-Performance Computing</p>
    <p class="hp-card__desc">GPU-accelerated methods to scale up the simulation and analysis of large biomedical problems.</p>
  </div>
</div>

<section class="hp-section">
  <h2 id="grants">Grants</h2><hr />
  <div class="hp-grid hp-grid--3">
    {% for grant in site.data.grants %}
      <div class="hp-card">
        <div class="hp-card__icon"><i class="fa-solid {{ grant.icon | default: 'fa-award' }}" aria-hidden="true"></i></div>
        {% if grant.subtitle %}<span class="hp-card__sub">{{ grant.subtitle }}</span>{% endif %}
        <p class="hp-card__title">{{ grant.title }}</p>
        <p class="hp-card__desc">{{ grant.description }}</p>
      </div>
    {% endfor %}
  </div>
</section>

<section class="hp-section">
  <h2 id="projects">Projects &amp; Tools</h2><hr />
  <div class="hp-grid hp-grid--tools">
    {% for project in site.data.projects %}
      {% if project.url contains "gitlab" %}{% assign brand = "fa-gitlab" %}{% else %}{% assign brand = "fa-github" %}{% endif %}
      <a class="hp-card hp-card--tool" href="{{ project.url }}">
        <div class="hp-card__icon"><i class="fa-brands {{ brand }}" aria-hidden="true"></i></div>
        <p class="hp-card__title">{{ project.title }}</p>
        <p class="hp-card__desc">{{ project.description }}</p>
      </a>
    {% endfor %}
  </div>
</section>

<section class="hp-section">
  <h2 id="news">Latest News</h2><hr />
  <div class="hp-grid hp-grid--3">
    {% for item in site.data.news %}
      {% if item.url %}
        {% if item.url contains "://" or item.url contains "mailto" %}{% assign n_url = item.url %}{% else %}{% assign n_url = item.url | prepend: base_path %}{% endif %}
        <a class="hp-card" href="{{ n_url }}">
      {% else %}
        <div class="hp-card">
      {% endif %}
          <div class="hp-card__icon"><i class="fa-solid {{ item.icon | default: 'fa-bullhorn' }}" aria-hidden="true"></i></div>
          {% if item.tag %}<span class="hp-card__sub">{{ item.tag }}</span>{% endif %}
          <p class="hp-card__title">{{ item.title }}</p>
          {% if item.excerpt %}<p class="hp-card__desc">{{ item.excerpt }}</p>{% endif %}
      {% if item.url %}</a>{% else %}</div>{% endif %}
    {% endfor %}
  </div>
</section>
