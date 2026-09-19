+++
title = "Research Software | Anas Bouali"
hascode = false
rss = "Overview of research software packages and implementations in Julia and Python."
+++

~~~
<style>
@import url('https://fonts.googleapis.com/css2?family=Newsreader:ital,opsz,wght@0,6..72,500;0,6..72,600;1,6..72,500&family=Public+Sans:wght@400;500;600;700&family=JetBrains+Mono:wght@500;600&display=swap');

/* ================= Base typography & Cool Archival Palette ================= */
body {
  background-color: #F7F9FA;
  background-image: radial-gradient(circle, #D1D9E0 0.8px, transparent 0.8px);
  background-size: 24px 24px;
}

.franklin-content {
  font-family: "Public Sans", Arial, Helvetica, sans-serif;
  color: #1A242B;
  line-height: 1.7;
}

.franklin-content h1,
.franklin-content h2,
.franklin-content h3 {
  border-bottom: 0 !important;
  padding-bottom: 0 !important;
  font-family: "Newsreader", Georgia, "Times New Roman", serif;
  color: #11181C;
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
  background: #1E4D5B; /* Deep Academic Teal/Slate */
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

/* ================= Intro banner ================= */
.franklin-content .software-intro {
  font-size: 1.05rem;
  line-height: 1.7;
  color: #3A4A54;
  background: #E8EEF2; /* Cool slate grey */
  border: 1px solid #D1D9E0;
  border-radius: 4px;
  padding: 1.1rem 1.4rem;
  margin: 0.4rem 0 2.4rem;
}

/* ================= Cards ================= */
.franklin-content .software-card {
  --accent: #1E4D5B; /* Deep Teal */
  --accent-soft: #E8EEF2;
  background: #ffffff;
  border: 1px solid #D1D9E0;
  border-radius: 4px;
  padding: 1.5rem;
  margin-bottom: 1.5rem;
  box-shadow: 0 1px 3px rgba(26, 36, 43, 0.04);
  transition: transform 0.18s ease, box-shadow 0.18s ease, border-color 0.18s ease;
  max-width: 100%;
  box-sizing: border-box;
  min-width: 0;
}

.franklin-content .software-card.featured {
  --accent: #2B6B7C; /* Brighter Slate/Teal for featured */
  --accent-soft: #E0EBEF;
}

.franklin-content .software-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 20px rgba(26, 36, 43, 0.08);
  border-color: var(--accent);
}

.franklin-content .software-header {
  display: flex;
  align-items: center;
  gap: 0.6rem;
  margin-bottom: 0.8rem;
  flex-wrap: wrap;
}

.franklin-content .lang-badge {
  font-family: "JetBrains Mono", monospace;
  font-size: 0.7rem;
  font-weight: 600;
  padding: 0.2rem 0.6rem;
  border-radius: 4px;
  text-transform: uppercase;
  letter-spacing: 0.05em;
}

.franklin-content .lang-badge.julia {
  background: #EFEAEC;
  color: #4A4565; /* Muted Indigo */
  border: 1px solid #4A4565;
}

.franklin-content .lang-badge.python {
  background: #E6EBE8;
  color: #3D5A4C; /* Muted Moss */
  border: 1px solid #3D5A4C;
}

.franklin-content .status-badge {
  font-family: "JetBrains Mono", monospace;
  font-size: 0.7rem;
  font-weight: 700;
  color: #2B6B7C;
  background: #E0EBEF;
  border: 1px solid #2B6B7C;
  border-radius: 4px;
  padding: 0.2rem 0.6rem;
  text-transform: uppercase;
  letter-spacing: 0.05em;
}

.franklin-content .software-title {
  font-family: "Newsreader", Georgia, serif;
  font-size: 1.4rem;
  font-weight: 600;
  color: #11181C;
  margin: 0 0 0.6rem 0;
}

.franklin-content .software-desc {
  font-size: 0.95rem;
  line-height: 1.65;
  color: #3A4A54;
  margin-bottom: 1.2rem;
}

/* ================= Figures ================= */
.franklin-content .software-card img {
  width: 100%;
  max-width: 100%;
  height: auto;
  padding: 0;
  margin: 0 auto;
  display: block;
  box-sizing: border-box;
  object-fit: contain;
}

.franklin-content .software-visual {
  margin: 1rem auto 0.8rem;
  max-width: 950px;
  width: 100%;
  border-radius: 4px;
  overflow: hidden;
  border: 1px solid #D1D9E0;
  background: #ffffff;
  line-height: 0;
  box-sizing: border-box;
}

.franklin-content .software-visual img,
.franklin-content .software-visual video {
  width: 100%;
  max-width: 100%;
  height: auto;
  padding: 0;
  margin: 0 auto;
  display: block;
  object-fit: contain;
}

/* ================= Example grids ================= */
.franklin-content .example-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(min(220px, 100%), 1fr));
  gap: 1rem;
  margin: 1rem 0;
  max-width: 100%;
}

.franklin-content .example-item {
  background: #F7F9FA;
  border: 1px dashed #D1D9E0; /* Ledger/Notebook style dashed border */
  border-radius: 4px;
  padding: 0.8rem;
  text-align: center;
  overflow: hidden;
  min-width: 0;
  box-sizing: border-box;
}

.franklin-content .example-item h4 {
  font-family: "Public Sans", sans-serif;
  font-size: 0.85rem;
  font-weight: 600;
  color: #5B6B75;
  margin: 0.6rem 0 0 0;
}

.franklin-content .example-item img {
  width: 100%;
  max-width: 100%;
  height: auto;
  padding: 0;
  margin: 0 auto;
  display: block;
  object-fit: contain;
  background: #ffffff;
  border-radius: 4px;
  border: 1px solid #D1D9E0;
}

/* ================= Buttons ================= */
.franklin-content .software-links {
  display: flex;
  gap: 0.8rem;
  flex-wrap: wrap;
  margin-top: 1rem;
}

.franklin-content .btn-primary,
.franklin-content .btn-secondary {
  display: inline-flex;
  align-items: center;
  gap: 0.4rem;
  font-family: "Public Sans", sans-serif;
  font-size: 0.85rem;
  font-weight: 600;
  text-decoration: none;
  border-radius: 4px;
  padding: 0.5rem 1rem;
  transition: all 0.15s ease;
}

.franklin-content .btn-primary {
  background: var(--accent, #1E4D5B);
  color: #ffffff;
  box-shadow: none;
}

.franklin-content .btn-primary:hover {
  filter: brightness(1.15);
  transform: translateY(-1px);
}

.franklin-content .btn-secondary {
  background: #ffffff;
  color: #1A242B;
  border: 1px solid #D1D9E0;
}

.franklin-content .btn-secondary:hover {
  background: #F7F9FA;
  border-color: var(--accent, #1E4D5B);
  color: var(--accent, #1E4D5B);
}

/* ================= Global Links ================= */
.franklin-content a:not(.btn-primary):not(.btn-secondary) {
  color: #1E4D5B;
  text-decoration: none;
  font-weight: 600;
  border-bottom: 1px dashed #1E4D5B;
  transition: all 0.15s ease;
}

.franklin-content a:not(.btn-primary):not(.btn-secondary):hover {
  border-bottom-style: solid;
}

/* ================= Responsive ================= */
@media (max-width: 560px) {
  .franklin-content .software-card { padding: 1.2rem; }
  .franklin-content .software-links { flex-direction: column; }
  .franklin-content .btn-primary,
  .franklin-content .btn-secondary { width: 100%; justify-content: center; }
  .franklin-content .example-grid { grid-template-columns: 1fr; }
}
</style>
~~~

# Research Software

~~~
<div class="software-intro">
  Open-source research implementations, numerical solvers, and simulation tools developed during my research. All packages are documented and designed for reproducibility.
</div>
~~~

## Featured Package

~~~
<div class="software-card featured">
  <div class="software-header">
    <span class="lang-badge julia">Julia</span>
    <span class="status-badge">New (2026)</span>
  </div>
  <h3 class="software-title">FT_Observer.jl</h3>
  <p class="software-desc">
    Observer synthesis and peak reduction for the SIR model with output feedback under budget-constrained interventions. This package provides robust numerical tools for epidemiological optimal control, accompanying recent research on constrained interventions.
  </p>
  <div class="software-visual">
    <img src="/assets/ft_vs_ekf_u3tilde.gif" alt="FT-DREM vs EKF finite-time convergence animation">
  </div>
  <div class="software-links">
    <a href="https://anasxbouali.github.io/FT_Observer/stable/" class="btn-primary" target="_blank" rel="noopener">View Documentation ↗</a>
  </div>
</div>
~~~

## Julia Packages

~~~
<div class="software-card">
  <div class="software-header">
    <span class="lang-badge julia">Julia</span>
  </div>
  <h3 class="software-title">SIRcontrol.jl</h3>
  <p class="software-desc">
    A Julia package for solving optimal control problems with SIR epidemiological models, supporting both constant and time-varying transmission rates.
  </p>
  <div class="example-grid">
    <div class="example-item">
      <img src="/assets/figSIR_git.jpg" alt="Constant Transmission Rate">
      <h4>Constant Transmission Rate</h4>
    </div>
    <div class="example-item">
      <img src="/assets/fig2cSIR.jpg" alt="Piecewise Constant Transmission Rate">
      <h4>Piecewise Constant Rate</h4>
    </div>
  </div>
  <div class="software-links">
    <a href="https://anasxbouali.github.io/SIRcontrol.jl/dev/" class="btn-primary" target="_blank" rel="noopener">View Documentation ↗</a>
  </div>
</div>
~~~

~~~
<div class="software-card">
  <div class="software-header">
    <span class="lang-badge julia">Julia</span>
  </div>
  <h3 class="software-title">LossControl.jl</h3>
  <p class="software-desc">
    A comprehensive package for solving optimal control problems with loss control regions, featuring multiple classical control examples.
  </p>
  <div class="example-grid">
    <div class="example-item">
      <img src="/assets/zer0.gif" alt="Zermelo Navigation">
      <h4>Zermelo Navigation</h4>
    </div>
    <div class="example-item">
      <img src="/assets/ho0.gif" alt="Harmonic Oscillator">
      <h4>Harmonic Oscillator</h4>
    </div>
  </div>
  <div class="software-links">
    <a href="https://control-toolbox.org/LossControl.jl/stable/" class="btn-primary" target="_blank" rel="noopener">View Documentation ↗</a>
  </div>
</div>
~~~

~~~
<div class="software-card">
  <div class="software-header">
    <span class="lang-badge julia">Julia</span>
  </div>
  <h3 class="software-title">RegHybridOCP.jl</h3>
  <p class="software-desc">
    Novel regularization scheme for optimal control problems with hybrid dynamics featuring state-dependent discontinuities.
  </p>
  <div class="example-grid">
    <div class="example-item">
      <img src="/assets/x.jpg" alt="Regularization Scheme State">
      <h4>Example 1</h4>
    </div>
    <div class="example-item">
      <img src="/assets/xx.jpg" alt="Regularization Scheme Control">
      <h4>Example 2</h4>
    </div>
  </div>
  <div class="software-links">
    <a href="https://github.com/AnasXbouali/Academic-example" class="btn-secondary" target="_blank" rel="noopener">GitHub Repository</a>
  </div>
</div>
~~~

## Python Implementations

~~~
<div class="software-card">
  <div class="software-header">
    <span class="lang-badge python">Python</span>
  </div>
  <h3 class="software-title">SRoptimization.py</h3>
  <p class="software-desc">
    Investigation of reduced-precision optimization algorithms using stochastic rounding techniques for improved computational efficiency.
  </p>
  <div class="example-grid">
    <div class="example-item">
      <img src="/assets/optim1.jpg" alt="Optimization Results 1">
      <h4>Convergence Analysis</h4>
    </div>
    <div class="example-item">
      <img src="/assets/optim2.jpg" alt="Optimization Results 2">
      <h4>Precision Comparison</h4>
    </div>
  </div>
</div>
~~~

~~~
<div class="software-card">
  <div class="software-header">
    <span class="lang-badge python">Python</span>
  </div>
  <h3 class="software-title">SRode.py</h3>
  <p class="software-desc">
    Investigation of reduced-precision methods for solving ordinary differential equations using the midpoint method with stochastic rounding techniques for improved computational efficiency.
  </p>
  <div class="example-grid">
    <div class="example-item">
      <img src="/assets/S_example.jpg" alt="Susceptible (S) Model Example">
      <h4>S (Susceptible)</h4>
    </div>
    <div class="example-item">
      <img src="/assets/I_example.jpg" alt="Infected (I) Model Example">
      <h4>I (Infected)</h4>
    </div>
    <div class="example-item">
      <img src="/assets/R_example.jpg" alt="Recovered (R) Model Example">
      <h4>R (Recovered)</h4>
    </div>
  </div>
  <div class="software-links">
    <a href="https://github.com/AnasXbouali/SR-ODEs-epidemiology" class="btn-secondary" target="_blank" rel="noopener">GitHub Repository</a>
  </div>
</div>
~~~

## Get in Touch

All code is available on my [GitHub profile](https://github.com/AnasXbouali). For questions about implementation details, reproducibility, or collaboration opportunities, feel free to [contact me](mailto:anas.bouali@inrae.fr).
