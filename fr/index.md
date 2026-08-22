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
<style>
.rmap-wrap { background:#ffffff; border:1px solid #d9e2ec; border-radius:12px; padding:1rem; box-shadow:0 1px 2px rgba(16,42,67,.06); }
.rmap-hint { font-size:.85rem; color:#526d82; text-align:center; margin:.6rem 0 0; font-style:italic; }
.rmap { width:100%; height:auto; display:block; }
.rmap text { font-family: Georgia, "Times New Roman", serif; fill:#3d3d3d; pointer-events:none; }
.rmap .bt { font-size:21px; }
.rmap .kt { font-size:12px; }
.rmap circle { fill:#ffffff; }
.rmap .big { stroke-width:4; cursor:pointer; }
.rmap .kid circle { stroke-width:2.5; }
.rmap line { stroke-width:2; }
.rmap .kids { opacity:0; transition:opacity .3s ease; pointer-events:none; }
.rmap .topic:hover .kids { opacity:1; pointer-events:auto; }
.g-oc .big{stroke:#2b3eb5;} .g-oc .kid circle,.g-oc line{stroke:#4c6ef5;}
.g-no .big{stroke:#e03131;} .g-no .kid circle,.g-no line{stroke:#fa5252;}
.g-mo .big{stroke:#2f9e44;} .g-mo .kid circle,.g-mo line{stroke:#51cf66;}
.g-se .big{stroke:#f08c00;} .g-se .kid circle,.g-se line{stroke:#ffa94d;}
.g-sc .big{stroke:#0c8599;} .g-sc .kid circle,.g-sc line{stroke:#22b8cf;}
@media (hover:none){ .rmap .kids{opacity:1; pointer-events:auto;} }
</style>

<div class="rmap-wrap">
<svg class="rmap" viewBox="0 0 1000 500" role="img" aria-label="Carte des intérêts de recherche">

  <!-- ================= Contrôle optimal ================= -->
  <g class="topic g-oc">
    <g class="kids">
      <line x1="320" y1="115" x2="165" y2="85"/>
      <line x1="320" y1="115" x2="475" y2="80"/>
      <line x1="320" y1="115" x2="135" y2="215"/>
      <line x1="320" y1="115" x2="275" y2="245"/>
      <line x1="320" y1="115" x2="405" y2="235"/>
      <g class="kid"><circle cx="165" cy="85" r="40"/><text class="kt" x="165" y="81"><tspan x="165">Systèmes</tspan><tspan x="165" dy="13">hybrides</tspan></text></g>
      <g class="kid"><circle cx="475" cy="80" r="40"/><text class="kt" x="475" y="67"><tspan x="475">Régions de</tspan><tspan x="475" dy="13">contrôle</tspan><tspan x="475" dy="13">avec perte</tspan></text></g>
      <g class="kid"><circle cx="135" cy="215" r="44"/><text class="kt" x="135" y="206"><tspan x="135">Principe du</tspan><tspan x="135" dy="13">maximum</tspan><tspan x="135" dy="13">de Pontryagin</tspan></text></g>
      <g class="kid"><circle cx="275" cy="245" r="40"/><text class="kt" x="275" y="241"><tspan x="275">Synthèse</tspan><tspan x="275" dy="13">optimale</tspan></text></g>
      <g class="kid"><circle cx="405" cy="235" r="40"/><text class="kt" x="405" y="231"><tspan x="405">Contrôles</tspan><tspan x="405" dy="13">par retour</tspan></text></g>
    </g>
    <circle class="big" cx="320" cy="115" r="70"/>
    <text class="bt" x="320" y="109"><tspan x="320">Contrôle</tspan><tspan x="320" dy="24">optimal</tspan></text>
  </g>

  <!-- ================= Optimisation numérique ================= -->
  <g class="topic g-no">
    <g class="kids">
      <line x1="720" y1="115" x2="605" y2="190"/>
      <line x1="720" y1="115" x2="865" y2="205"/>
      <g class="kid"><circle cx="605" cy="190" r="40"/><text class="kt" x="605" y="186"><tspan x="605">Méthodes</tspan><tspan x="605" dy="13">de tir</tspan></text></g>
      <g class="kid"><circle cx="865" cy="205" r="44"/><text class="kt" x="865" y="201"><tspan x="865">Schémas de</tspan><tspan x="865" dy="13">régularisation</tspan></text></g>
    </g>
    <circle class="big" cx="720" cy="115" r="74"/>
    <text class="bt" x="720" y="109"><tspan x="720">Optimisation</tspan><tspan x="720" dy="24">numérique</tspan></text>
  </g>

  <!-- ================= Modélisation ================= -->
  <g class="topic g-mo">
    <g class="kids">
      <line x1="520" y1="265" x2="670" y2="255"/>
      <line x1="520" y1="265" x2="545" y2="395"/>
      <g class="kid"><circle cx="670" cy="255" r="40"/><text class="kt" x="670" y="251"><tspan x="670">Allocation</tspan><tspan x="670" dy="13">de ressources</tspan></text></g>
      <g class="kid"><circle cx="545" cy="395" r="42"/><text class="kt" x="545" y="399">Épidémiologie</text></g>
    </g>
    <circle class="big" cx="520" cy="265" r="66"/>
    <text class="bt" x="520" y="272">Modélisation</text>
  </g>

  <!-- ================= Estimation d'état ================= -->
  <g class="topic g-se">
    <g class="kids">
      <line x1="295" y1="375" x2="155" y2="395"/>
      <line x1="295" y1="375" x2="440" y2="430"/>
      <g class="kid"><circle cx="155" cy="395" r="40"/><text class="kt" x="155" y="391"><tspan x="155">Observateur</tspan><tspan x="155" dy="13">KKL</tspan></text></g>
      <g class="kid"><circle cx="440" cy="430" r="44"/><text class="kt" x="440" y="421"><tspan x="440">Filtre de</tspan><tspan x="440" dy="13">Kalman</tspan><tspan x="440" dy="13">étendu</tspan></text></g>
    </g>
    <circle class="big" cx="295" cy="375" r="62"/>
    <text class="bt" x="295" y="369"><tspan x="295">Estimation</tspan><tspan x="295" dy="24">d'état</tspan></text>
  </g>

  <!-- ================= Calcul scientifique ================= -->
  <g class="topic g-sc">
    <g class="kids">
      <line x1="795" y1="335" x2="665" y2="405"/>
      <g class="kid"><circle cx="665" cy="405" r="42"/><text class="kt" x="665" y="401"><tspan x="665">Arrondi</tspan><tspan x="665" dy="13">stochastique</tspan></text></g>
    </g>
    <circle class="big" cx="795" cy="335" r="62"/>
    <text class="bt" x="795" y="329"><tspan x="795">Calcul</tspan><tspan x="795" dy="24">scientifique</tspan></text>
  </g>

</svg>
</div>
~~~

## Liens

~~~
<div class="link-grid">
  <a href="mailto:anas.bouali@outlook.com" class="link-card">
    <span class="link-icon">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round">
        <rect x="2" y="4" width="20" height="16" rx="2"/>
        <path d="m22 7-10 5L2 7"/>
      </svg>
    </span>
    <span>Courriel</span>
  </a>

  <a href="https://scholar.google.com/citations?user=CdSC_JsAAAAJ&hl=fr" target="_blank" rel="noopener" class="link-card">
    <span class="link-icon">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round">
        <path d="M22 10 12 5 2 10l10 5 10-5z"/>
        <path d="M6 12v5c0 1.5 3 3 6 3s6-1.5 6-3v-5"/>
      </svg>
    </span>
    <span>Google Scholar</span>
  </a>

  <a href="https://github.com/AnasXbouali" target="_blank" rel="noopener" class="link-card">
    <span class="link-icon">
      <svg viewBox="0 0 24 24" fill="currentColor">
        <path d="M12 2C6.477 2 2 6.477 2 12c0 4.42 2.865 8.166 6.839 9.489.5.092.682-.217.682-.482 0-.237-.009-.866-.013-1.7-2.782.603-3.369-1.34-3.369-1.34-.454-1.155-1.11-1.462-1.11-1.462-.908-.62.069-.608.069-.608 1.003.07 1.531 1.03 1.531 1.03.892 1.529 2.341 1.087 2.91.831.092-.646.35-1.087.636-1.337-2.22-.252-4.555-1.11-4.555-4.943 0-1.091.39-1.984 1.029-2.683-.103-.253-.446-1.27.098-2.647 0 0 .84-.269 2.75 1.025A9.578 9.578 0 0 1 12 6.836c.85.004 1.705.114 2.504.336 1.909-1.294 2.747-1.025 2.747-1.025.546 1.377.203 2.394.1 2.647.64.699 1.028 1.592 1.028 2.683 0 3.842-2.339 4.687-4.566 4.935.359.309.678.919.678 1.852 0 1.336-.012 2.415-.012 2.743 0 .267.18.578.688.48C19.138 20.161 22 16.416 22 12c0-5.523-4.477-10-10-10z"/>
      </svg>
    </span>
    <span>GitHub</span>
  </a>

  <a href="https://www.linkedin.com/in/anas-bouali-276539215/" target="_blank" rel="noopener" class="link-card">
    <span class="link-icon">
      <svg viewBox="0 0 24 24" fill="currentColor">
        <path d="M20.45 20.45h-3.55v-5.57c0-1.33-.02-3.04-1.85-3.04-1.85 0-2.13 1.45-2.13 2.94v5.67H9.36V9h3.41v1.56h.05c.47-.9 1.63-1.85 3.36-1.85 3.6 0 4.27 2.37 4.27 5.45v6.29zM5.34 7.43a2.06 2.06 0 1 1 0-4.13 2.06 2.06 0 0 1 0 4.13zm1.78 13.02H3.56V9h3.56v11.45zM22.22 0H1.77C.79 0 0 .77 0 1.72v20.56C0 23.23.79 24 1.77 24h20.45c.98 0 1.78-.77 1.78-1.72V1.72C24 .77 23.2 0 22.22 0z"/>
      </svg>
    </span>
    <span>LinkedIn</span>
  </a>
</div>
~~~
