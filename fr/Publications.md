+++
title = "Publications | Anas Bouali"
hascode = false
rss = "Publications scientifiques d'Anas Bouali sur le contrôle optimal, la dynamique hybride et la modélisation mathématique."
isfr = true
+++

~~~
<style>
@import url('https://fonts.googleapis.com/css2?family=Newsreader:ital,opsz,wght@0,6..72,400;0,6..72,600;1,6..72,400&family=Public+Sans:wght@400;500;600&family=JetBrains+Mono:wght@400;500&display=swap');

/* ============================================================
   Thème "Archive de Chercheur" — Grille, Encre et Papier
   ============================================================ */

body {
  background-color: #FDFBF7;
  background-image: radial-gradient(circle, rgba(44, 62, 80, 0.12) 0.8px, transparent 0.8px);
  background-size: 24px 24px;
}

.franklin-content {
  font-family: "Public Sans", sans-serif;
  color: #2C3E50;
}

.franklin-content h1, .franklin-content h2 {
  border-bottom: 0 !important;
  padding-bottom: 0 !important;
  font-family: "Newsreader", Georgia, serif;
  color: #17202A;
}

.franklin-content h1 {
  font-size: clamp(2rem, 4vw, 2.8rem);
  font-weight: 600;
  letter-spacing: -0.02em;
  margin-top: 0.5em;
  margin-bottom: 0.2em;
}

.franklin-content h1::after {
  content: "";
  display: block;
  width: 60px;
  height: 3px;
  background: #6E2C00; /* Accent Terre de Sienne */
  margin-top: 0.4rem;
}

.franklin-content h2 {
  font-family: "JetBrains Mono", monospace;
  font-size: 0.9rem;
  font-weight: 500;
  margin-top: 3rem;
  margin-bottom: 1.5rem;
  padding-left: 0;
  border-left: 0;
  border-bottom: 1px solid #D5D8DC;
  padding-bottom: 0.3rem;
  text-transform: uppercase;
  letter-spacing: 0.1em;
  color: #5D6D7E;
}

.franklin-content .publications-intro {
  font-family: "Newsreader", serif;
  font-size: 1.15rem;
  font-style: italic;
  line-height: 1.6;
  color: #2C3E50;
  background: rgba(255, 255, 255, 0.6); /* Semi-transparent pour laisser voir la grille */
  border-top: 1px solid #AAB7B8;
  border-bottom: 1px solid #AAB7B8;
  border-radius: 0;
  padding: 1.2rem 1rem;
  margin: 1.5rem 0 3rem;
  text-align: center;
}

/* Palette Académique Personnalisée */
.franklin-content .publication           { --pub: #1A5276; --pub-soft: #EBF5FB; } /* Revue: Bleu Académique */
.franklin-content .publication.t-conf    { --pub: #6E2C00; --pub-soft: #FDF2E9; } /* Conférence: Terre de Sienne */
.franklin-content .publication.t-preprint{ --pub: #7D6608; --pub-soft: #FEF9E7; } /* Prépub: Ocre / Chemise Manila */
.franklin-content .publication.t-chapter { --pub: #4A235A; --pub-soft: #F4ECF7; } /* Chapitre: Prune de Reliure */
.franklin-content .publication.t-thesis  { --pub: #17202A; --pub-soft: #EAEDED; } /* Thèse: Graphite / Encre */

.franklin-content .publication {
  background: #ffffff;
  border: 1px solid #D5D8DC;
  border-radius: 2px; /* Coins droits, style fiche cartonnée */
  padding: 1.5rem;
  margin-bottom: 1.5rem;
  box-shadow: 4px 4px 0px #E5E7E9; /* Ombre dure */
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.franklin-content .publication:hover {
  transform: translate(-2px, -2px);
  box-shadow: 6px 6px 0px var(--pub); /* L'ombre prend la couleur du domaine au survol */
}

.franklin-content .publication-meta {
  display: flex;
  align-items: center;
  gap: 0.8rem;
  flex-wrap: wrap;
  margin-bottom: 0.8rem;
}

.franklin-content .publication-year {
  font-family: "JetBrains Mono", monospace;
  font-size: 0.8rem;
  font-weight: 500;
  color: #2C3E50;
  background: transparent;
  border: 1px dashed #AAB7B8; /* Bordure pointillée type ticket */
  border-radius: 0;
  padding: 0.15rem 0.5rem;
}

.franklin-content .publication-type {
  font-family: "JetBrains Mono", monospace;
  font-size: 0.7rem;
  font-weight: 500;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: var(--pub);
  background: var(--pub-soft);
  border-radius: 0;
  padding: 0.25rem 0.6rem;
  border: 1px solid var(--pub);
}

.franklin-content .publication h3 {
  font-family: "Newsreader", Georgia, serif;
  font-size: 1.3rem;
  font-weight: 600;
  line-height: 1.4;
  color: #17202A;
  margin: 0.2rem 0 0.6rem;
}

.franklin-content .publication-authors {
  font-family: "Public Sans", sans-serif;
  font-size: 0.95rem;
  color: #5D6D7E;
  margin: 0.2rem 0;
}

.franklin-content .publication-venue {
  font-family: "Newsreader", Georgia, serif; /* Serif pour le nom des journaux */
  font-size: 0.95rem;
  font-style: italic;
  color: #34495E;
  margin: 0.2rem 0 1rem;
}

/* Boutons style "Base de données / Tampon" */
.franklin-content a.publication-link,
.franklin-content a.publication-link:hover {
  display: inline-block;
  font-family: "JetBrains Mono", monospace;
  font-size: 0.75rem;
  font-weight: 500;
  color: var(--pub);
  text-decoration: none;
  background: transparent;
  border: 1px solid var(--pub);
  border-radius: 2px;
  padding: 0.3rem 0.7rem;
  letter-spacing: 0.05em;
  text-transform: uppercase;
  transition: all 0.2s ease;
  box-shadow: none;
  filter: none;
}

.franklin-content a.publication-link:hover {
  background: var(--pub);
  color: #ffffff;
  transform: none;
}

@media (max-width: 560px) {
  .franklin-content .publication { padding: 1.2rem; box-shadow: 2px 2px 0px #E5E7E9; }
  .franklin-content .publication:hover { box-shadow: 4px 4px 0px var(--pub); }
}
</style>
~~~

# Publications

~~~
<div class="publications-intro">
  Recherches évaluées par les pairs sur le contrôle optimal, dynamiques hybride/non lisse,
  les méthodes numériques et la biologie mathématique.
</div>
~~~

## Prépublications récentes

~~~
<div class="publication t-conf">
  <div class="publication-meta">
    <span class="publication-year">2026</span>
    <span class="publication-type">Article de conférence</span>
  </div>
  <h3>Observer synthesis and peak reduction for the SIR model with output feedback under budget-constrained interventions</h3>
  <p class="publication-authors">Co-auteurs : Radosław Patelski, Alain Rapaport, Denis Efimov et Rosane Ushirobira</p>
  <p class="publication-venue">À paraître dans la 65<sup>e</sup> IEEE Conference on Decision and Control, 2026</p>
  <a class="publication-link" href="https://hal.science/hal-05699171">Lire sur HAL ↗</a>
</div>
~~~

~~~
<div class="publication t-preprint">
  <div class="publication-meta">
    <span class="publication-year">2026</span>
    <span class="publication-type">Manuscrit soumis</span>
  </div>
  <h3>Low-Precision Arithmetic for Solving ODEs: A Case Study in Epidemiological Modeling</h3>
  <p class="publication-authors">Co-auteurs : El-Mehdi El Arar et Rémi Garcia</p>
  <p class="publication-venue">Soumis, 2026</p>
  <a class="publication-link" href="https://hal.science/hal-05653284">Lire sur HAL ↗</a>
</div>
~~~

## Articles de revues

~~~
<div class="publication">
  <div class="publication-meta">
    <span class="publication-year">2026</span>
    <span class="publication-type">Article de revue</span>
  </div>
  <h3>Regularization of optimal control problems on stratified domains using additional controls</h3>
  <p class="publication-authors">Co-auteurs : Alain Rapaport et Terence Bayen</p>
  <p class="publication-venue">SIAM Journal on Control and Optimization, Vol. 64, N° 4, p. 2689–2714, 2026</p>
  <a class="publication-link" href="https://epubs.siam.org/doi/10.1137/25M1746896">DOI ↗</a>
</div>
~~~

~~~
<div class="publication">
  <div class="publication-meta">
    <span class="publication-year">2026</span>
    <span class="publication-type">Article de revue</span>
  </div>
  <h3>On the problem of minimizing the epidemic final size for SIR model by social distancing</h3>
  <p class="publication-authors">Co-auteurs : Pierre-Alexandre Bliman, Patrice Loisel, Alain Rapaport et Arnaud Virelizier</p>
  <p class="publication-venue">Mathematical Biosciences and Engineering, 2026</p>
  <a class="publication-link" href="https://www.aimspress.com/article/doi/10.3934/mbe.2026022">DOI ↗</a>
</div>
~~~

~~~
<div class="publication">
  <div class="publication-meta">
    <span class="publication-year">2026</span>
    <span class="publication-type
