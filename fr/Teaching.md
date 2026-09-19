+++
title = "Enseignement et encadrement | Anas Bouali"
hascode = false
rss = "Détails de l'expérience d'enseignement et de l'encadrement d'étudiants par Anas Bouali."
isfr = true
+++

~~~
<style>
@import url('https://fonts.googleapis.com/css2?family=Newsreader:ital,opsz,wght@0,6..72,500;0,6..72,600;1,6..72,500&family=Public+Sans:wght@400;500;600;700&family=JetBrains+Mono:wght@500;600&display=swap');

/* ============================================================
   Teaching & Supervision page — Bespoke Archival Academic Style
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

.franklin-content h3 {
  font-size: 1.25rem;
  font-weight: 600;
  margin-top: 1.8rem;
  margin-bottom: 0.9rem;
  padding-left: 0;
  border-left: 0;
}

/* Teaching Position Cards */
.franklin-content .teaching-position {
  --accent: #A85741; /* Rouille */
  background: #ffffff;
  border: 1px solid #D6D1C9;
  border-left: 1px solid #D6D1C9;
  border-radius: 4px;
  padding: 1.3rem 1.5rem;
  margin-bottom: 1.4rem;
  box-shadow: 0 1px 3px rgba(43, 40, 38, 0.04);
  transition: transform 0.18s ease, box-shadow 0.18s ease, border-color 0.18s ease;
}

.franklin-content .teaching-position:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 20px rgba(43, 40, 38, 0.08);
  border-color: var(--accent);
}

.franklin-content .position-title {
  font-family: "Newsreader", Georgia, serif;
  font-size: 1.35rem;
  font-weight: 600;
  color: #1A1817;
  margin: 0 0 0.2rem 0;
}

.franklin-content .position-meta {
  font-size: 0.95rem;
  color: #756E67;
  margin-bottom: 1.1rem;
  padding-bottom: 0.7rem;
  border-bottom: 1px dashed #D6D1C9;
}

.franklin-content .position-meta strong {
  color: #A85741;
  font-weight: 600;
}

/* Course Sub-cards (Ledger/Notebook style) */
.franklin-content .course {
  background: #F9F8F6;
  border: 1px dashed #D6D1C9;
  border-radius: 4px;
  padding: 1rem 1.2rem;
  margin: 0.9rem 0;
}

.franklin-content .course-title {
  font-family: "Newsreader", Georgia, serif;
  font-size: 1.1rem;
  font-weight: 600;
  color: #1A1817;
  margin: 0 0 0.3rem 0;
}

.franklin-content .course-meta {
  font-size: 0.85rem;
  font-style: italic;
  color: #756E67;
  margin-bottom: 0.7rem;
}

.franklin-content .course-content {
  font-size: 0.93rem;
  line-height: 1.6;
  color: #4A4541;
}

.franklin-content .course-content ul {
  margin: 0.5rem 0;
  padding-left: 1.3rem;
}

.franklin-content .course-content li {
  margin: 0.25rem 0;
}

/* Supervision Cards */
.franklin-content .supervision-item {
  --accent: #6B4C5A; /* Prune */
  background: #ffffff;
  border: 1px solid #D6D1C9;
  border-left: 1px solid #D6D1C9;
  border-radius: 4px;
  padding: 1.2rem 1.5rem;
  margin-bottom: 1.1rem;
  box-shadow: 0 1px 3px rgba(43, 40, 38, 0.04);
  transition: transform 0.18s ease, box-shadow 0.18s ease, border-color 0.18s ease;
}

.franklin-content .supervision-item:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 20px rgba(43, 40, 38, 0.08);
  border-color: var(--accent);
}

.franklin-content .supervision-type {
  font-family: "JetBrains Mono", monospace;
  font-size: 0.68rem;
  font-weight: 700;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  color: #6B4C5A;
  background: #EFEAEC;
  border: 1px solid #6B4C5A;
  border-radius: 4px;
  padding: 0.2rem 0.6rem;
  display: inline-block;
  margin-bottom: 0.7rem;
}

.franklin-content .supervision-year {
  font-family: "JetBrains Mono", Menlo, Consolas, monospace;
  font-size: 0.85rem;
  font-weight: 600;
  color: #4A4541;
  background: #EFECE6;
  border: 1px solid #D6D1C9;
  border-radius: 4px;
  padding: 0.14rem 0.5rem;
  margin-left: 0.5rem;
}

.franklin-content .supervision-topic {
  font-family: "Newsreader", Georgia, serif;
  font-size: 1.15rem;
  font-weight: 600;
  color: #1A1817;
  margin: 0.5rem 0;
}

.franklin-content .supervision-topic em {
  font-style: italic;
  color: #4A6B7C; /* Ardoise */
}

.franklin-content .supervision-details {
  font-size: 0.93rem;
  color: #756E67;
  line-height: 1.6;
}

@media (max-width: 560px) {
  .franklin-content .teaching-position,
  .franklin-content .supervision-item {
    padding: 1rem 1.1rem;
  }
  .franklin-content .course {
    padding: 0.9rem 1rem;
  }
}
</style>
~~~

# Enseignement et encadrement

## Expérience d'enseignement

~~~
<div class="teaching-position">
  <h3 class="position-title">Attaché temporaire d'enseignement et de recherche (ATER)</h3>
  <p class="position-meta"><strong>Université de Toulouse</strong> · 2026–2027</p>
  
  <div class="course">
    <h4 class="course-title">Analyse 2</h4>
    <p class="course-meta">Licence 2 Mathématiques · Intégration et séries numériques</p>
  </div>
  
  <div class="course">
    <h4 class="course-title">Introduction aux statistiques et initiation à R</h4>
    <p class="course-meta">Licence 2 Mathématiques</p>
  </div>
  
  <div class="course">
    <h4 class="course-title">Méthodes numériques</h4>
    <p class="course-meta">Licence 3 Mathématiques</p>
  </div>
</div>
~~~

~~~
<div class="teaching-position">
  <h3 class="position-title">Attaché temporaire d'enseignement et de recherche (ATER)</h3>
  <p class="position-meta"><strong>Avignon Université</strong> · 2023–2024</p>
  
  <div class="course">
    <h4 class="course-title">Analyse 1</h4>
    <p class="course-meta">Licence 1 Mathématiques et Informatique · 33 heures</p>
    <div class="course-content">
      <ul>
        <li>Fonctions élémentaires et leurs propriétés</li>
        <li>Dérivation et intégration</li>
        <li>Équations différentielles linéaires</li>
      </ul>
    </div>
  </div>
  
  <div class="course">
    <h4 class="course-title">Analyse 2</h4>
    <p class="course-meta">Licence 1 Mathématiques et Informatique · 21 heures</p>
    <div class="course-content">
      <ul>
        <li>Suites de nombres réels et limites</li>
        <li>Théorèmes fondamentaux sur les suites</li>
        <li>Comportement asymptotique et suites complexes</li>
      </ul>
    </div>
  </div>
  
  <div class="course">
    <h4 class="course-title">Algèbre 1</h4>
    <p class="course-meta">Licence 1 Mathématiques et Informatique · 27 heures</p>
    <div class="course-content">
      <ul>
        <li>Introduction à la logique et à la théorie des ensembles</li>
        <li>Arithmétique et trigonométrie</li>
        <li>Nombres complexes</li>
      </ul>
    </div>
  </div>
  
  <div class="course">
    <h4 class="course-title">Algèbre 2</h4>
    <p class="course-meta">Licence 1 Mathématiques et Informatique · 21 heures</p>
    <div class="course-content">
      <ul>
        <li>Systèmes linéaires et matrices</li>
        <li>Sous-espaces vectoriels</li>
        <li>Applications linéaires et déterminants</li>
      </ul>
    </div>
  </div>
  
  <div class="course">
    <h4 class="course-title">Mathématiques</h4>
    <p class="course-meta">Licence 1 Sciences de la Vie et de la Terre · 9 heures</p>
    <div class="course-content">
      <ul>
        <li>Étude de fonctions</li>
        <li>Dérivation et intégration</li>
      </ul>
    </div>
  </div>
</div>
~~~

~~~
<div class="teaching-position">
  <h3 class="position-title">Doctorant contractuel avec mission d'enseignement</h3>
  <p class="position-meta"><strong>Avignon Université</strong> · 2020–2023</p>
  
  <div class="course">
    <h4 class="course-title">Algèbre 1</h4>
    <p class="course-meta">Licence 1 Mathématiques · 27 heures</p>
    <div class="course-content">
      <ul>
        <li>Introduction à la logique et à la théorie des ensembles</li>
        <li>Arithmétique et trigonométrie</li>
        <li>Nombres complexes</li>
      </ul>
    </div>
  </div>
  
  <div class="course">
    <h4 class="course-title">Algèbre 2</h4>
    <p class="course-meta">Licence 1 Mathématiques · 21 heures</p>
    <div class="course-content">
      <ul>
        <li>Systèmes linéaires et matrices</li>
        <li>Sous-espaces vectoriels</li>
        <li>Applications linéaires et déterminants</li>
      </ul>
    </div>
  </div>
  
  <div class="course">
    <h4 class="course-title">Mathématiques</h4>
    <p class="course-meta">Licence 1 Sciences de la Vie et de la Terre · 9 heures</p>
    <div class="course-content">
      <ul>
        <li>Étude de fonctions</li>
        <li>Dérivation et intégration</li>
      </ul>
    </div>
  </div>
</div>
~~~

## Encadrement d'étudiants

~~~
<div class="supervision-item">
  <span class="supervision-type">Stage de Master 1</span>
  <span class="supervision-year">2026</span>
  <h4 class="supervision-topic">Sujet : <em>Méthodes numériques pour les problèmes de contrôle optimal non lisses</em></h4>
  <p class="supervision-details">Co-encadré avec Olivier Cots, Université de Toulouse.</p>
</div>
~~~

~~~
<div class="supervision-item">
  <span class="supervision-type">Stage de Master 2</span>
  <span class="supervision-year">2026</span>
  <h4 class="supervision-topic">Sujet : <em>Contrôle optimal en épidémiologie des maladies à transmission vectorielle</em></h4>
  <p class="supervision-details">Co-encadré avec Alain Rapaport et Patrice Loisel, UMR MISTEA, Centre INRAE Occitanie-Montpellier.</p>
</div>
~~~

~~~
<div class="supervision-item">
  <span class="supervision-type">Stage de Master 2</span>
  <span class="supervision-year">2025</span>
  <h4 class="supervision-topic">Sujet : <em>Contrôle optimal en épidémiologie avec émergence de variants</em></h4>
  <p class="supervision-details">Co-encadré avec Alain Rapaport et Patrice Loisel, UMR MISTEA, Centre INRAE Occitanie-Montpellier.</p>
</div>
~~~
