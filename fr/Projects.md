+++
title = "Projets de recherche | Anas Bouali"
hascode = false
rss = "Un résumé des projets de recherche et des collaborations."
isfr = true
+++

~~~
<style>
@import url('https://fonts.googleapis.com/css2?family=Newsreader:ital,opsz,wght@0,6..72,500;0,6..72,600;1,6..72,500&family=Public+Sans:wght@400;500;600;700&family=JetBrains+Mono:wght@500;600&display=swap');

/* ============================================================
   Projets de recherche — Bespoke Archival Academic Style
   (Matched exactly to the rest of the portfolio)
   ============================================================ */

body {
  background-color: #F9F8F6;
  background-image: radial-gradient(circle, #D6D1C9 0.8px, transparent 0.8px);
  background-size: 24px 24px;
}

.franklin-content {
  font-family: "Public Sans", Arial, Helvetica, sans-serif;
  color: #2B2826;
}

.franklin-content h1,
.franklin-content h2,
.franklin-content h3 {
  border-bottom: 0 !important;
  padding-bottom: 0 !important;
  font-family: "Newsreader", Georgia, "Times New Roman", serif;
  color: #1A1817;
}

.franklin-content h1 {
  font-size: clamp(2.1rem, 4.5vw, 2.8rem);
  font-weight: 600;
  letter-spacing: -0.015em;
  margin-top: 0.4em;
  margin-bottom: 0.6em;
}

.franklin-content h1::after {
  content: "";
  display: block;
  width: 76px;
  height: 2px;
  margin-top: 0.55rem;
  border-radius: 0;
  background: #A85741; /* Accent Rouille */
}

.franklin-content h2 {
  font-size: 1.5rem;
  font-weight: 600;
  letter-spacing: -0.01em;
  margin-top: 2.4rem;
  margin-bottom: 1.2rem;
  padding-left: 0;
  border-left: 0;
}

.franklin-content .projects-intro {
  font-size: 1.05rem;
  line-height: 1.7;
  color: #4A4541;
  background: #EFECE6;
  border: 1px solid #D6D1C9;
  border-radius: 4px;
  padding: 1.1rem 1.4rem;
  margin: 0.4rem 0 2.4rem;
}

/* Palette Archival par Type de Projet */
.franklin-content .project-card {
  --sec: #A85741; /* Rouille (En cours) */
  --sec-soft: #F4EBE8;
  background: #ffffff;
  border: 1px solid #D6D1C9;
  border-left: 1px solid #D6D1C9;
  border-radius: 4px;
  padding: 1.2rem 1.5rem 1.3rem;
  margin-bottom: 1.25rem;
  box-shadow: 0 1px 3px rgba(43, 40, 38, 0.04);
  transition: transform 0.18s ease, box-shadow 0.18s ease, border-color 0.18s ease;
}

.franklin-content .project-card.p-prev {
  --sec: #4A6B7C; /* Ardoise (Précédent) */
  --sec-soft: #E8EEF2;
}

.franklin-content .project-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 20px rgba(43, 40, 38, 0.08);
  border-color: var(--sec); /* La bordure prend la couleur du statut au survol */
}

.franklin-content .project-status {
  display: inline-block;
  font-family: "JetBrains Mono", monospace;
  font-size: 0.68rem;
  font-weight: 700;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  border-radius: 999px;
  padding: 0.3rem 0.75rem;
  margin-bottom: 0.7rem;
  color: var(--sec);
  background: var(--sec-soft);
  border: 1px solid var(--sec);
}

.franklin-content .project-title {
  font-family: "Newsreader", Georgia, serif;
  font-size: 1.27rem;
  font-weight: 600;
  line-height: 1.42;
  color: #1A1817;
  margin: 0.15rem 0 0.5rem;
}

.franklin-content .project-collaborators {
  font-size: 0.93rem;
  color: #5C5651;
  margin: 0.15rem 0 0.85rem;
  line-height: 1.6;
}

.franklin-content .project-collaborators strong {
  color: #4A4541;
  font-weight: 600;
}

.franklin-content .project-collaborators a {
  display: inline-block;
  color: var(--sec);
  text-decoration: none;
  font-weight: 600;
  border-bottom: 1px dashed var(--sec);
  transition: all 0.15s ease;
}

.franklin-content .project-collaborators a:hover {
  border-bottom-style: solid;
}

.franklin-content .project-description {
  font-size: 0.95rem;
  line-height: 1.65;
  color: #4A4541;
  margin: 0;
}

@media (max-width: 560px) {
  .franklin-content .project-card {
    padding: 1rem 1.1rem 1.1rem;
  }
  .franklin-content .project-title {
    font-size: 1.15rem;
  }
}
</style>
~~~

# Projets de recherche

~~~
<div class="projects-intro">
  Une vue d'ensemble des projets de recherche actuels et passés en contrôle optimal, méthodes numériques et modélisation mathématique.
</div>
~~~

## Projets en cours

~~~
<div class="project-card">
  <span class="project-status s-current">En cours</span>
  <h3 class="project-title">ANR NOCIME (Participant)</h3>
  <p class="project-collaborators">
    <strong>Collaborateurs :</strong> 
    <a href="https://sites.google.com/site/alainrapaport" target="_blank" rel="noopener">Alain Rapaport</a> et 
    <a href="https://who.rocq.inria.fr/Pierre-Alexandre.Bliman/" target="_blank" rel="noopener">Pierre-Alexandre Bliman</a>
  </p>
  <p class="project-description">
    Un projet de recherche sur les problèmes de contrôle optimal avec des critères non standards et leurs applications à l'épidémiologie.
  </p>
</div>
~~~

~~~
<div class="project-card">
  <span class="project-status s-current">En cours</span>
  <h3 class="project-title">Projet Jeune Chercheur PGMO</h3>
  <p class="project-collaborators">
    <strong>Collaborateur :</strong> 
    <a href="https://ocots.github.io/" target="_blank" rel="noopener">Olivier Cots</a>
  </p>
  <p class="project-description">
    Développement d'une nouvelle technique de régularisation pour la résolution de problèmes de contrôle optimal hybrides.
  </p>
</div>
~~~

## Projets précédents

~~~
<div class="project-card p-prev">
  <span class="project-status s-prev">Précédent</span>
  <h3 class="project-title">BOUM pour les jeunes de la SMAI</h3>
  <p class="project-collaborators">
    <strong>Collaborateurs :</strong> 
    <a href="https://rubenchenevat.github.io/" target="_blank" rel="noopener">Ruben Chenevat</a> et 
    <a href="https://dadjo-mahugnon-gildas.github.io/site-web/" target="_blank" rel="noopener">Gildas Dadjo</a>
  </p>
  <p class="project-description">
    Organisation d'une journée de conférence axée sur l'optimisation, la modélisation et le contrôle, qui s'est tenue à l'INRAE Montpellier le 12 juin 2025.
  </p>
</div>
~~~

~~~
<div class="project-card p-prev">
  <span class="project-status s-prev">Précédent</span>
  <h3 class="project-title">PEPS JCJC 2024</h3>
  <p class="project-collaborators">
    <strong>Collaborateur :</strong> 
    <a href="https://mehdielarar.github.io/" target="_blank" rel="noopener">El-Mehdi El Arar</a>
  </p>
  <p class="project-description">
    Étude des effets de l'arrondi stochastique sur la résolution de problèmes de contrôle optimal.
  </p>
</div>
~~~
