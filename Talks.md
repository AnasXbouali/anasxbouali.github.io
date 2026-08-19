+++
title = "Talks & Presentations"
hascode = false
rss = "A list of talks, presentations, and posters by Anas Bouali."
+++

~~~
<style>
@import url('https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,500;9..144,600;9..144,700&family=Inter:wght@400;500;600;700&family=JetBrains+Mono:wght@500;600&display=swap');

/* ============================================================
   Talks page theme — self-contained, this page only.
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

.franklin-content h2.t-workshop { border-left-color: #1971c2; }
.franklin-content h2.t-poster    { border-left-color: #b45309; }

/* 3) Intro banner */
.franklin-content .talks-intro {
  font-size: 1.05rem;
  line-height: 1.7;
  color: #23425f;
  background: linear-gradient(120deg, #e6fcf5 0%, #e7f5ff 100%);
  border: 1px solid #c5e8f0;
  border-radius: 14px;
  padding: 1.1rem 1.4rem;
  margin: 0.4rem 0 2.4rem;
}

/* 4) Year cards */
.franklin-content .talk-section {
  background: #ffffff;
  border: 1px solid #d9e2ec;
  border-left: 5px solid #0b7285;
  border-radius: 12px;
  padding: 1.2rem 1.5rem;
  margin-bottom: 1.4rem;
  box-shadow: 0 1px 2px rgba(16, 42, 67, 0.06);
  transition: transform 0.18s ease, box-shadow 0.18s ease;
}

.franklin-content .talk-section.t-workshop { border-left-color: #1971c2; }
.franklin-content .talk-section.t-poster    { border-left-color: #b45309; }

.franklin-content .talk-section:hover {
  transform: translateY(-3px);
  box-shadow: 0 12px 26px rgba(16, 42, 67, 0.12);
}

.franklin-content .year-heading {
  font-family: "JetBrains Mono", Menlo, Consolas, monospace;
  font-size: 1.1rem;
  font-weight: 700;
  color: #102a43;
  margin: 0 0 1rem 0;
  padding-bottom: 0.6rem;
  border-bottom: 1px dashed #d9e2ec;
}

/* 5) Talk items */
.franklin-content .talk-item {
  display: flex;
  align-items: flex-start;
  gap: 0.8rem;
  padding: 0.7rem 0;
  border-bottom: 1px solid #f1f5f9;
}

.franklin-content .talk-item:last-child {
  border-bottom: 0;
  padding-bottom: 0;
}

.franklin-content .talk-month {
  flex-shrink: 0;
  font-family: "JetBrains Mono", Menlo, Consolas, monospace;
  font-size: 0.75rem;
  font-weight: 600;
  color: #0b7285;
  background: #e6fcf5;
  border-radius: 6px;
  padding: 0.25rem 0.6rem;
  min-width: 60px;
  text-align: center;
}

.talk-section.t-workshop .talk-month { color: #1971c2; background: #e7f5ff; }
.talk-section.t-poster    .talk-month { color: #b45309; background: #fff4e6; }

.franklin-content .talk-body {
  flex: 1;
  min-width: 0;
}

.franklin-content .talk-title {
  font-family: "Fraunces", Georgia, serif;
  font-size: 1.05rem;
  font-weight: 600;
  color: #102a43;
  margin: 0 0 0.2rem 0;
  line-height: 1.4;
}

.franklin-content .talk-venue {
  font-size: 0.88rem;
  font-style: italic;
  color: #526d82;
  margin: 0;
  line-height: 1.5;
}

/* 6) Poster badge */
.franklin-content .poster-badge {
  display: inline-block;
  font-size: 0.68rem;
  font-weight: 700;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  color: #b45309;
  background: #fff4e6;
  border-radius: 999px;
  padding: 0.2rem 0.6rem;
  margin-left: 0.5rem;
  vertical-align: middle;
}

/* 7) Small screens */
@media (max-width: 560px) {
  .franklin-content .talk-section { padding: 1rem 1.1rem; }
  .franklin-content .talk-item { flex-direction: column; gap: 0.4rem; }
  .franklin-content .talk-month { align-self: flex-start; }
}
</style>
~~~

# 💬 Talks & Presentations

~~~
<div class="talks-intro">
  A collection of my presentations at seminars, conferences, and workshops.
</div>
~~~

## Seminars & Conferences

~~~
<div class="talk-section">
  <h3 class="year-heading">2026</h3>
  <div class="talk-item">
    <span class="talk-month">May</span>
    <div class="talk-body">
      <p class="talk-title">Séminaire SPOT</p>
      <p class="talk-venue">INP-ENSEEIHT, Toulouse (France)</p>
    </div>
  </div>
  <div class="talk-item">
    <span class="talk-month">March</span>
    <div class="talk-body">
      <p class="talk-title">Séminaire MIPA</p>
      <p class="talk-venue">Nîmes Université (France)</p>
    </div>
  </div>
  <div class="talk-item">
    <span class="talk-month">March</span>
    <div class="talk-body">
      <p class="talk-title">Journée SMAI MODE</p>
      <p class="talk-venue">Nice (France)</p>
    </div>
  </div>
  <div class="talk-item">
    <span class="talk-month">January</span>
    <div class="talk-body">
      <p class="talk-title">Séminaire du Centre Automatique et Systèmes</p>
      <p class="talk-venue">Mines Paris-PSL, Paris (France)</p>
    </div>
  </div>
</div>
~~~

~~~
<div class="talk-section">
  <h3 class="year-heading">2025</h3>
  <div class="talk-item">
    <span class="talk-month">December</span>
    <div class="talk-body">
      <p class="talk-title">Séminaire McTAO</p>
      <p class="talk-venue">Centre Inria d'Université Côte d'Azur, Antibes (France)</p>
    </div>
  </div>
  <div class="talk-item">
    <span class="talk-month">December</span>
    <div class="talk-body">
      <p class="talk-title">Séminaire CRAN Nancy</p>
      <p class="talk-venue">Lorraine University, Nancy (France)</p>
    </div>
  </div>
  <div class="talk-item">
    <span class="talk-month">November</span>
    <div class="talk-body">
      <p class="talk-title">Présentation de l'Axe Systèmes Dynamiques (UMR MISTEA - INRAE), Évaluation HCéres 2025</p>
      <p class="talk-venue">Montpellier (France)</p>
    </div>
  </div>
  <div class="talk-item">
    <span class="talk-month">November</span>
    <div class="talk-body">
      <p class="talk-title">PGMO Days</p>
      <p class="talk-venue">EDF Lab Paris-Saclay (France)</p>
    </div>
  </div>
  <div class="talk-item">
    <span class="talk-month">May</span>
    <div class="talk-body">
      <p class="talk-title">12ème Congrès SMAI 2025</p>
      <p class="talk-venue">Carcans-Maubuissons (France)</p>
    </div>
  </div>
  <div class="talk-item">
    <span class="talk-month">February</span>
    <div class="talk-body">
      <p class="talk-title">Séminaire Analyse, Phénomènes Stochastiques et Applications</p>
      <p class="talk-venue">LMBA, Université Bretagne Occidentale, Brest (France)</p>
    </div>
  </div>
</div>
~~~

~~~
<div class="talk-section">
  <h3 class="year-heading">2024</h3>
  <div class="talk-item">
    <span class="talk-month">December</span>
    <div class="talk-body">
      <p class="talk-title">Séminaire Axe Systèmes Dynamiques</p>
      <p class="talk-venue">UMR MISTEA, Montpellier (France)</p>
    </div>
  </div>
  <div class="talk-item">
    <span class="talk-month">October</span>
    <div class="talk-body">
      <p class="talk-title">Julia Days & Optimization</p>
      <p class="talk-venue">INP-ENSEEIHT, Toulouse (France)</p>
    </div>
  </div>
  <div class="talk-item">
    <span class="talk-month">September</span>
    <div class="talk-body">
      <p class="talk-title">Atelier Viabilité</p>
      <p class="talk-venue">Institut des Systèmes Complexes, Paris (France)</p>
    </div>
  </div>
  <div class="talk-item">
    <span class="talk-month">June</span>
    <div class="talk-body">
      <p class="talk-title">French-German-Spanish Conference on Optimization</p>
      <p class="talk-venue">Oviedo University, Gijón (Spain)</p>
    </div>
  </div>
  <div class="talk-item">
    <span class="talk-month">June</span>
    <div class="talk-body">
      <p class="talk-title">Journée Contrôle Optimal et Applications</p>
      <p class="talk-venue">FRUMAM, Marseille (France)</p>
    </div>
  </div>
  <div class="talk-item">
    <span class="talk-month">March</span>
    <div class="talk-body">
      <p class="talk-title">Journée SMAI MODE</p>
      <p class="talk-venue">INSA Lyon (France)</p>
    </div>
  </div>
</div>
~~~

~~~
<div class="talk-section">
  <h3 class="year-heading">2023</h3>
  <div class="talk-item">
    <span class="talk-month">November</span>
    <div class="talk-body">
      <p class="talk-title">Séminaire SPOC</p>
      <p class="talk-venue">IMB, Université de Bourgogne, Dijon (France)</p>
    </div>
  </div>
  <div class="talk-item">
    <span class="talk-month">October</span>
    <div class="talk-body">
      <p class="talk-title">Journées Annuelles du GdR MOA</p>
      <p class="talk-venue">Perpignan University, Perpignan (France)</p>
    </div>
  </div>
  <div class="talk-item">
    <span class="talk-month">September</span>
    <div class="talk-body">
      <p class="talk-title">Séminaire CRAN Nancy</p>
      <p class="talk-venue">Lorraine University, Nancy (France)</p>
    </div>
  </div>
  <div class="talk-item">
    <span class="talk-month">June</span>
    <div class="talk-body">
      <p class="talk-title">Journée Contrôle Optimal et Applications</p>
      <p class="talk-venue">FRUMAM, Marseille (France)</p>
    </div>
  </div>
  <div class="talk-item">
    <span class="talk-month">January</span>
    <div class="talk-body">
      <p class="talk-title">Séminaire Modélisation, Optimisation, Dynamique</p>
      <p class="talk-venue">XLIM, Limoges University (France)</p>
    </div>
  </div>
</div>
~~~

~~~
<div class="talk-section">
  <h3 class="year-heading">2022</h3>
  <div class="talk-item">
    <span class="talk-month">November</span>
    <div class="talk-body">
      <p class="talk-title">PGMO Days</p>
      <p class="talk-venue">EDF Lab Paris-Saclay (France)</p>
    </div>
  </div>
  <div class="talk-item">
    <span class="talk-month">May</span>
    <div class="talk-body">
      <p class="talk-title">French-German-Portuguese Conference on Optimization</p>
      <p class="talk-venue">Porto University (Portugal)</p>
    </div>
  </div>
  <div class="talk-item">
    <span class="talk-month">April</span>
    <div class="talk-body">
      <p class="talk-title">Séminaire du Laboratoire de Modélisation Pluridisciplinaire et Simulations</p>
      <p class="talk-venue">Perpignan University (France)</p>
    </div>
  </div>
  <div class="talk-item">
    <span class="talk-month">January</span>
    <div class="talk-body">
      <p class="talk-title">Séminaire Modélisation, Optimisation, Dynamique</p>
      <p class="talk-venue">XLIM, Limoges University (France)</p>
    </div>
  </div>
</div>
~~~

## Workshops & Summer Schools

~~~
<div class="talk-section t-workshop">
  <h3 class="year-heading">2022</h3>
  <div class="talk-item">
    <span class="talk-month">September</span>
    <div class="talk-body">
      <p class="talk-title">Domain Decomposition for Optimal Control Problems</p>
      <p class="talk-venue">CIRM, Luminy, Marseille (France)</p>
    </div>
  </div>
  <div class="talk-item">
    <span class="talk-month">July</span>
    <div class="talk-body">
      <p class="talk-title">Numerical Tools and Examples of Optimal Control, "Sprint: Control Toolbox"</p>
      <p class="talk-venue">Nice (France)</p>
    </div>
  </div>
  <div class="talk-item">
    <span class="talk-month">June</span>
    <div class="talk-body">
      <p class="talk-title">Workshop: "Optimal Control Theory"</p>
      <p class="talk-venue">INSA Rouen Normandie (France)</p>
    </div>
  </div>
  <div class="talk-item">
    <span class="talk-month">June</span>
    <div class="talk-body">
      <p class="talk-title">Journée SMAI MODE</p>
      <p class="talk-venue">Limoges University (France)</p>
    </div>
  </div>
</div>
~~~

## Posters

~~~
<div class="talk-section t-poster">
  <h3 class="year-heading">2022</h3>
  <div class="talk-item">
    <span class="talk-month">September</span>
    <div class="talk-body">
      <p class="talk-title">Domain Decomposition for Optimal Control Problems <span class="poster-badge">Poster</span></p>
      <p class="talk-venue">CIRM, Luminy, Marseille (France)</p>
    </div>
  </div>
  <div class="talk-item">
    <span class="talk-month">June</span>
    <div class="talk-body">
      <p class="talk-title">Journée SMAI MODE <span class="poster-badge">Poster</span></p>
      <p class="talk-venue">Limoges University (France)</p>
    </div>
  </div>
</div>
~~~
