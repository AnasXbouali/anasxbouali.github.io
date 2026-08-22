@def title = "Anas Bouali | Mathématicien appliqué"
@def tags = ["home", "academic", "landing"]
@def hascode = false

~~~
<style>
@import url('https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,500;9..144,600;9..144,700&family=Inter:wght@400;500;600;700&family=JetBrains+Mono:wght@500;600&display=swap');

/* ============================================================
   Homepage theme — self-contained, this page only.
   Palette synced with basic.css (ink #102a43, teal #0b7285).
   ============================================================ */

.franklin-content {
  font-family: "Inter", Arial, Helvetica, sans-serif;
  color: #102a43;
  line-height: 1.7;
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

.franklin-content h2 {
  font-size: 1.6rem;
  font-weight: 600;
  letter-spacing: -0.01em;
  margin-top: 2.6rem;
  margin-bottom: 1.4rem;
  padding-left: 0.8rem;
  border-left: 5px solid #0b7285;
}

/* 2) Hero Banner */
.franklin-content .hero-banner {
  background: linear-gradient(135deg, #e6fcf5 0%, #e7f5ff 100%);
  border: 1px solid #c5e8f0;
  border-radius: 16px;
  padding: 2.5rem 2rem;
  margin-bottom: 2.5rem;
  text-align: left;
}

.franklin-content .hero-name {
  font-family: "Fraunces", Georgia, serif;
  font-size: clamp(2.2rem, 5vw, 3.2rem);
  font-weight: 700;
  color: #102a43;
  margin: 0 0 0.4rem 0;
  letter-spacing: -0.02em;
  line-height: 1.1;
}

.franklin-content .hero-title {
  font-size: 1.15rem;
  font-weight: 600;
  color: #0b7285;
  margin: 0 0 1rem 0;
  letter-spacing: 0.02em;
}

.franklin-content .hero-role {
  font-size: 1.05rem;
  color: #23425f;
  margin: 0;
  line-height: 1.6;
}

.franklin-content .hero-role a {
  color: #0b7285;
  font-weight: 600;
  text-decoration: none;
  border-bottom: 1px dashed #0b7285;
  transition: all 0.15s ease;
}

.franklin-content .hero-role a:hover {
  border-bottom-style: solid;
  background: rgba(11, 114, 133, 0.08);
  border-radius: 4px;
  padding: 0 2px;
}

/* 3) Info Cards (for Current Position & Academic Background) */
.franklin-content .info-card {
  background: #ffffff;
  border: 1px solid #d9e2ec;
  border-left: 5px solid #1971c2;
  border-radius: 12px;
  padding: 1.5rem;
  margin-bottom: 1.5rem;
  box-shadow: 0 1px 2px rgba(16, 42, 67, 0.06);
  transition: transform 0.18s ease, box-shadow 0.18s ease;
}

.franklin-content .info-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 12px 26px rgba(16, 42, 67, 0.12);
}

.franklin-content .info-card p {
  margin-top: 0;
  margin-bottom: 1rem;
  font-size: 0.98rem;
  color: #23425f;
}

.franklin-content .info-card p:last-child {
  margin-bottom: 0;
}

.franklin-content .info-card a {
  color: #1971c2;
  font-weight: 600;
  text-decoration: none;
  border-bottom: 1px dashed #1971c2;
  transition: all 0.15s ease;
}

.franklin-content .info-card a:hover {
  border-bottom-style: solid;
  background: #e7f5ff;
  border-radius: 4px;
  padding: 0 2px;
}

/* 4) Research Interests Image Container */
.franklin-content .image-container {
  background: #ffffff;
  border: 1px solid #d9e2ec;
  border-radius: 12px;
  padding: 1rem;
  box-shadow: 0 1px 2px rgba(16, 42, 67, 0.06);
  text-align: center;
}

.franklin-content .image-container img {
  width: 100%;
  max-width: 900px;
  height: auto;
  padding: 0;
  margin: 0 auto;
  display: block;
  border-radius: 8px;
  box-sizing: border-box;
  object-fit: contain;
}

/* 5) Links Grid */
.franklin-content .link-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 1rem;
  margin-top: 1rem;
}

.franklin-content .link-card {
  display: flex;
  align-items: center;
  gap: 0.75rem;
  background: #ffffff;
  border: 1px solid #d9e2ec;
  border-radius: 10px;
  padding: 1rem 1.2rem;
  text-decoration: none;
  color: #102a43;
  font-weight: 600;
  font-size: 0.95rem;
  transition: all 0.18s ease;
  box-shadow: 0 1px 2px rgba(16, 42, 67, 0.04);
}

.franklin-content .link-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 20px rgba(16, 42, 67, 0.1);
  border-color: #0b7285;
  color: #0b7285;
}

.franklin-content .link-icon {
  font-size: 1.3rem;
  flex-shrink: 0;
}

/* 6) Small screens */
@media (max-width: 560px) {
  .franklin-content .hero-banner { padding: 1.8rem 1.2rem; }
  .franklin-content .info-card { padding: 1.2rem; }
  .franklin-content .link-grid { grid-template-columns: 1fr; }
}
</style>
~~~

~~~
<div class="hero-banner">
  <h1 class="hero-name">Anas Bouali</h1>
  <p class="hero-title">Mathématicien appliqué</p>
  <p class="hero-role">
    Contrôle optimal · Systèmes hybrides · Optimisation numérique<br>
    Chercheur postdoctoral en mathématiques appliquées au 
    <a href="https://mistea.montpellier.hub.inrae.fr/" target="_blank" rel="noopener">Centre INRAE Occitanie-Montpellier</a>
  </p>
</div>
~~~

## Profil de recherche

Je travaille sur le contrôle optimal, les systèmes dynamiques hybrides et non lisses, et les méthodes numériques pour les problèmes de contrôle contraint. Mes recherches combinent une analyse mathématique rigoureuse et des approches computationnelles, avec des applications motivées par l'épidémiologie et la biologie mathématique.

## Poste actuel

~~~
<div class="info-card">
  <p>
    Depuis septembre 2024, je suis chercheur postdoctoral au Centre INRAE Occitanie-Montpellier (UMR MISTEA). 
  </p>
  <p>
    Je travaille sur le <a href="https://sites.google.com/view/nocime" target="_blank" rel="noopener">projet ANR NOCIME</a> avec 
    <a href="https://sites.google.com/site/alainrapaport" target="_blank" rel="noopener">Alain Rapaport</a> et 
    <a href="https://who.rocq.inria.fr/Pierre-Alexandre.Bliman/" target="_blank" rel="noopener">Pierre-Alexandre Bliman</a>. 
    Ce projet aborde de nouveaux problèmes de contrôle optimal avec des fonctions de coût non standard motivées par l'épidémiologie.
  </p>
</div>
~~~

## Parcours académique

~~~
<div class="info-card">
  <p>
    <strong>2023–2024 :</strong> Attaché temporaire d'enseignement et de recherche (ATER) à Avignon Université.
  </p>
  <p>
    <strong>2020–2023 :</strong> Doctorat à Avignon Université sous la direction de Térence Bayen et de 
    <a href="https://www.unilim.fr/pages_perso/loic.bourdin/" target="_blank" rel="noopener">Loïc Bourdin</a>. 
    Mes travaux ont porté sur l'établissement de conditions nécessaires d'optimalité pour des problèmes de contrôle optimal hybrides et sur le développement de schémas numériques adaptés. 
    La <a href="https://theses.hal.science/tel-04335766v1" target="_blank" rel="noopener">thèse de doctorat est disponible ici</a>.
  </p>
  <p>
    <strong>Auparavant :</strong> stage de master au Laboratoire de Mathématiques Blaise Pascal sous la direction d'
    <a href="https://lmbp.uca.fr/~munch/" target="_blank" rel="noopener">Arnaud Münch</a>. 
    Ce travail a donné lieu à un <a href="https://raw.githubusercontent.com/AnasXbouali/anasxbouali.github.io/main/_assets/Memoire.pdf" target="_blank" rel="noopener">mémoire de master, disponible ici</a>.
  </p>
</div>
~~~

## Intérêts de recherche

~~~
<div class="image-container">
  <img src="/assets/map.svg" alt="Carte des intérêts de recherche">
</div>
~~~

## Liens

~~~
<div class="link-grid">
  <a href="mailto:anas.bouali@outlook.com" class="link-card">
    <span class="link-icon">📧</span>
    <span>Courriel</span>
  </a>
  <a href="https://scholar.google.com/citations?user=CdSC_JsAAAAJ&hl=fr" target="_blank" rel="noopener" class="link-card">
    <span class="link-icon">🎓</span>
    <span>Google Scholar</span>
  </a>
  <a href="https://github.com/AnasXbouali" target="_blank" rel="noopener" class="link-card">
    <span class="link-icon">💻</span>
    <span>GitHub</span>
  </a>
  <a href="https://www.linkedin.com/in/anas-bouali-276539215/" target="_blank" rel="noopener" class="link-card">
    <span class="link-icon">💼</span>
    <span>LinkedIn</span>
  </a>
  <a href="https://mistea.montpellier.hub.inrae.fr/" target="_blank" rel="noopener" class="link-card">
    <span class="link-icon">🏛️</span>
    <span>UMR MISTEA, INRAE</span>
  </a>
</div>
~~~
