@def title = "Anas Bouali | Applied Mathematician"
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

/* new — sized, centered SVG icons */
.franklin-content .link-icon {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  flex-shrink: 0;
  width: 22px;
  height: 22px;
  color: #0b7285;                /* matches accent */
  transition: color 0.18s ease, transform 0.18s ease;
}

.franklin-content .link-card:hover .link-icon {
  color: #0b7285;
  transform: scale(1.08);
}

.franklin-content .link-icon svg {
  width: 100%;
  height: 100%;
  display: block;
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
  <p class="hero-title">Applied Mathematician</p>
  <p class="hero-role">
    Optimal control · Hybrid systems · Numerical optimisation<br>
    Postdoctoral Researcher in Applied Mathematics at 
    <a href="https://mistea.montpellier.hub.inrae.fr/" target="_blank" rel="noopener">Centre INRAE Occitanie-Montpellier</a>
  </p>
</div>
~~~

## Research profile

I work on optimal control, hybrid and non-smooth dynamical systems, and numerical methods for constrained control problems. My research combines rigorous mathematical analysis with computational approaches, with applications motivated by epidemiology and mathematical biology.

## Current position

~~~
<div class="info-card">
  <p>
    Since September 2024, I have been a postdoctoral researcher at Centre INRAE Occitanie-Montpellier (UMR MISTEA). 
  </p>
  <p>
    I am working on the <a href="https://sites.google.com/view/nocime" target="_blank" rel="noopener">ANR project NOCIME</a> with 
    <a href="https://sites.google.com/site/alainrapaport" target="_blank" rel="noopener">Alain Rapaport</a> and 
    <a href="https://who.rocq.inria.fr/Pierre-Alexandre.Bliman/" target="_blank" rel="noopener">Pierre-Alexandre Bliman</a>. 
    The project addresses new optimal control problems with non-standard cost functions motivated by epidemiology.
  </p>
</div>
~~~

## Academic background

~~~
<div class="info-card">
  <p>
    <strong>2023–2024:</strong> Temporary Lecturer and Research Assistant (ATER) at Avignon Université.
  </p>
  <p>
    <strong>2020–2023:</strong> PhD at Avignon Université under the supervision of Térence Bayen and 
    <a href="https://www.unilim.fr/pages_perso/loic.bourdin/" target="_blank" rel="noopener">Loïc Bourdin</a>. 
    My research focused on deriving necessary optimality conditions for hybrid optimal control problems and developing adapted numerical schemes. 
    The <a href="https://theses.hal.science/tel-04335766v1" target="_blank" rel="noopener">doctoral thesis is available here</a>.
  </p>
  <p>
    <strong>Previously:</strong> Master's internship at the Laboratoire de Mathématiques Blaise Pascal under the supervision of 
    <a href="https://lmbp.uca.fr/~munch/" target="_blank" rel="noopener">Arnaud Münch</a>. 
    This work resulted in a <a href="https://raw.githubusercontent.com/AnasXbouali/anasxbouali.github.io/main/_assets/Memoire.pdf" target="_blank" rel="noopener">Master's thesis available here</a>.
  </p>
</div>
~~~

## Research interests

~~~
<div class="image-container">
  <img src="/assets/map.svg" alt="Research interests map">
</div>
~~~

## Links

~~~
<div class="link-grid">
  <a href="mailto:anas.bouali@outlook.com" class="link-card">
    <span class="link-icon">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round">
        <rect x="2" y="4" width="20" height="16" rx="2"/>
        <path d="m22 7-10 5L2 7"/>
      </svg>
    </span>
    <span>Email</span>
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

  <a href="https://mistea.montpellier.hub.inrae.fr/" target="_blank" rel="noopener" class="link-card">
    <span class="link-icon">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round">
        <path d="M3 21h18"/>
        <path d="M5 21V7l7-4 7 4v14"/>
        <path d="M9 21v-6h6v6"/>
        <path d="M10 9h4"/>
        <path d="M10 12h4"/>
      </svg>
    </span>
    <span>UMR MISTEA, INRAE</span>
  </a>
</div>
~~~
