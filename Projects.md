+++
title = "Research Projects | Anas Bouali"
hascode = false
rss = "A summary of research projects and collaborations"
+++

~~~
<style>
@import url('https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,500;9..144,600;9..144,700&family=Inter:wght@400;500;600;700&family=JetBrains+Mono:wght@500;600&display=swap');

/* ============================================================
   Projects page theme — self-contained, this page only.
   Palette synced with basic.css (ink #102a43, teal #0b7285).
   ============================================================ */

.franklin-content {
  font-family: "Inter", Arial, Helvetica, sans-serif;
  color: #102a43;
}

/* 1) Kill the grey separating lines from franklin.css */
.franklin-content h1,
.franklin-content h2,
.franklin-content h3 {
  border-bottom: 0 !important;
  padding-bottom: 0 !important;
  font-family: "Fraunces", Georgia, "Times New Roman", serif;
  color: #102a43;
}

.franklin-content h1 {
  font-size: clamp(2.1rem, 4.5vw, 2.8rem);
  font-weight: 700;
  letter-spacing: -0.015em;
  margin-top: 0.4em;
  margin-bottom: 0.6em;
}

.franklin-content h1::after {
  content: "";
  display: block;
  width: 76px;
  height: 5px;
  margin-top: 0.55rem;
  border-radius: 999px;
  background: linear-gradient(90deg, #0b7285, #1971c2);
}

/* 2) Section headings: vertical accent bar */
.franklin-content h2 {
  font-size: 1.6rem;
  font-weight: 600;
  letter-spacing: -0.01em;
  margin-top: 2.6rem;
  margin-bottom: 1.4rem;
  padding-left: 0.8rem;
  border-left: 5px solid #0b7285;
}

.franklin-content h2.p-prev { 
  border-left-color: #526d82; 
}

/* 3) Intro banner */
.franklin-content .projects-intro {
  font-size: 1.05rem;
  line-height: 1.7;
  color: #23425f;
  background: linear-gradient(120deg, #e6fcf5 0%, #e7f5ff 100%);
  border: 1px solid #c5e8f0;
  border-radius: 14px;
  padding: 1.1rem 1.4rem;
  margin: 0.4rem 0 2.4rem;
}

/* 4) Project cards */
.franklin-content .project-card {
  background: #ffffff;
  border: 1px solid #d9e2ec;
  border-left: 5px solid #0b7285;
  border-radius: 12px;
  padding: 1.4rem 1.6rem;
  margin-bottom: 1.2rem;
  box-shadow: 0 1px 2px rgba(16, 42, 67, 0.06);
  transition: transform 0.18s ease, box-shadow 0.18s ease;
}

.franklin-content .project-card.p-prev {
  border-left-color: #526d82;
}

.franklin-content .project-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 12px 26px rgba(16, 42, 67, 0.12);
}

/* 5) Status badges */
.franklin-content .project-status {
  display: inline-block;
  font-size: 0.7rem;
  font-weight: 700;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  border-radius: 999px;
  padding: 0.25rem 0.7rem;
  margin-bottom: 0.7rem;
}

.franklin-content .project-status.s-current {
  color: #0b7285;
  background: #e6fcf5;
}

.franklin-content .project-status.s-prev {
  color: #526d82;
  background: #f1f5f9;
}

/* 6) Project typography */
.franklin-content .project-title {
  font-family: "Fraunces", Georgia, serif;
  font-size: 1.3rem;
  font-weight: 700;
  color: #102a43;
  margin: 0 0 0.6rem 0;
  line-height: 1.35;
}

.franklin-content .project-collaborators {
  font-size: 0.9rem;
  color: #526d82;
  margin: 0 0 0.8rem 0;
  line-height: 1.6;
}

.franklin-content .project-collaborators strong {
  color: #102a43;
  font-weight: 600;
}

/* Collaborator links styled as subtle tags */
.franklin-content .project-collaborators a {
  display: inline-block;
  color: #0b7285;
  text-decoration: none;
  font-weight: 600;
  border-bottom: 1px dashed #0b7285;
  transition: all 0.15s ease;
}

.franklin-content .project-collaborators a:hover {
  color: #075866;
  border-bottom-style: solid;
  background: #e6fcf5;
  border-radius: 4px;
  padding: 0 2px;
}

.franklin-content .project-card.p-prev .project-collaborators a {
  color: #1971c2;
  border-bottom-color: #1971c2;
}

.franklin-content .project-card.p-prev .project-collaborators a:hover {
  color: #0c4a8a;
  background: #e7f5ff;
}

.franklin-content .project-description {
  font-size: 0.95rem;
  line-height: 1.65;
  color: #23425f;
  margin: 0;
}

/* 7) Small screens */
@media (max-width: 560px) {
  .franklin-content .project-card {
    padding: 1.1rem 1.2rem;
  }
  .franklin-content .project-title {
    font-size: 1.15rem;
  }
}
</style>
~~~

# Research projects

~~~
<div class="projects-intro">
  An overview of current and previous research projects in optimal control, numerical methods, and mathematical modelling.
</div>
~~~

## Current projects

~~~
<div class="project-card">
  <span class="project-status s-current">Current</span>
  <h3 class="project-title">ANR NOCIME</h3>
  <p class="project-collaborators">
    <strong>Collaborators:</strong> 
    <a href="https://sites.google.com/site/alainrapaport" target="_blank" rel="noopener">Alain Rapaport</a> and 
    <a href="https://who.rocq.inria.fr/Pierre-Alexandre.Bliman/" target="_blank" rel="noopener">Pierre-Alexandre Bliman</a>
  </p>
  <p class="project-description">
    A research project on optimal control problems with non-standard criteria and their applications to epidemiology.
  </p>
</div>
~~~

~~~
<div class="project-card">
  <span class="project-status s-current">Current</span>
  <h3 class="project-title">PGMO Young Researcher Project</h3>
  <p class="project-collaborators">
    <strong>Collaborator:</strong> 
    <a href="https://ocots.github.io/" target="_blank" rel="noopener">Olivier Cots</a>
  </p>
  <p class="project-description">
    Development of a new regularisation technique for solving hybrid optimal control problems.
  </p>
</div>
~~~

## Previous projects

~~~
<div class="project-card p-prev">
  <span class="project-status s-prev">Previous</span>
  <h3 class="project-title">BOUM pour les jeunes de la SMAI</h3>
  <p class="project-collaborators">
    <strong>Collaborators:</strong> 
    <a href="https://rubenchenevat.github.io/" target="_blank" rel="noopener">Ruben Chenevat</a> and 
    <a href="https://dadjo-mahugnon-gildas.github.io/site-web/" target="_blank" rel="noopener">Gildas Dadjo</a>
  </p>
  <p class="project-description">
    Organisation of a conference day focused on optimisation, modelling, and control, held at INRAE Montpellier on 12 June 2025.
  </p>
</div>
~~~

~~~
<div class="project-card p-prev">
  <span class="project-status s-prev">Previous</span>
  <h3 class="project-title">PEPS JCJC 2024</h3>
  <p class="project-collaborators">
    <strong>Collaborator:</strong> 
    <a href="https://mehdielarar.github.io/" target="_blank" rel="noopener">El-Mehdi El Arar</a>
  </p>
  <p class="project-description">
    Investigation of the effects of stochastic rounding on solving optimal control problems.
  </p>
</div>
~~~
