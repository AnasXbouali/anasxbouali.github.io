+++
title = "Publications | Anas Bouali"
hascode = false
rss = "Scientific publications by Anas Bouali on optimal control, hybrid dynamics, and mathematical modeling."
+++

~~~
<style>
@import url('https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,500;9..144,600;9..144,700&family=Inter:wght@400;500;600;700&family=JetBrains+Mono:wght@500;600&display=swap');

/* ============================================================
   Publications page theme — self-contained, this page only.
   Palette synced with basic.css (ink #102a43, teal #0b7285).
   ============================================================ */

.franklin-content {
  font-family: "Inter", Arial, Helvetica, sans-serif;
  color: #102a43;
}

/* 1) Kill the grey separating lines from franklin.css */
.franklin-content h1,
.franklin-content h2 {
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

/* short gradient accent under the page title (delete this block if you want nothing) */
.franklin-content h1::after {
  content: "";
  display: block;
  width: 76px;
  height: 5px;
  margin-top: 0.55rem;
  border-radius: 999px;
  background: linear-gradient(90deg, #0b7285, #1971c2);
}

/* 2) Section headings: vertical accent bar, no horizontal line */
.franklin-content h2 {
  font-size: 1.5rem;
  font-weight: 600;
  letter-spacing: -0.01em;
  margin-top: 2.4rem;
  margin-bottom: 1.2rem;
  padding-left: 0.8rem;
  border-left: 5px solid #0b7285;
}

/* 3) Intro banner */
.franklin-content .publications-intro {
  font-size: 1.05rem;
  line-height: 1.7;
  color: #23425f;
  background: linear-gradient(120deg, #e6fcf5 0%, #e7f5ff 100%);
  border: 1px solid #c5e8f0;
  border-radius: 14px;
  padding: 1.1rem 1.4rem;
  margin: 0.4rem 0 2.4rem;
}

/* 4) Cards — one accent colour per publication type */
.franklin-content .publication           { --pub: #0b7285; --pub-soft: #e6fcf5; } /* journal      */
.franklin-content .publication.t-conf    { --pub: #5f3dc4; --pub-soft: #f3f0ff; } /* conference   */
.franklin-content .publication.t-preprint{ --pub: #b45309; --pub-soft: #fff4e6; } /* preprint     */
.franklin-content .publication.t-chapter { --pub: #1971c2; --pub-soft: #e7f5ff; } /* book chapter */
.franklin-content .publication.t-thesis  { --pub: #a61e4d; --pub-soft: #fff0f6; } /* thesis       */

.franklin-content .publication {
  background: #ffffff;
  border: 1px solid #d9e2ec;
  border-left: 5px solid var(--pub);
  border-radius: 12px;
  padding: 1.2rem 1.5rem 1.3rem;
  margin-bottom: 1.25rem;
  box-shadow: 0 1px 2px rgba(16, 42, 67, 0.06);
  transition: transform 0.18s ease, box-shadow 0.18s ease;
}

.franklin-content .publication:hover {
  transform: translateY(-3px);
  box-shadow: 0 12px 26px rgba(16, 42, 67, 0.12);
}

.franklin-content .publication-meta {
  display: flex;
  align-items: center;
  gap: 0.6rem;
  flex-wrap: wrap;
  margin-bottom: 0.55rem;
}

.franklin-content .publication-year {
  font-family: "JetBrains Mono", Menlo, Consolas, monospace;
  font-size: 0.78rem;
  font-weight: 600;
  color: #526d82;
  background: #f8fafc;
  border: 1px solid #d9e2ec;
  border-radius: 6px;
  padding: 0.14rem 0.5rem;
}

.franklin-content .publication-type {
  font-size: 0.68rem;
  font-weight: 700;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  color: var(--pub);
  background: var(--pub-soft);
  border-radius: 999px;
  padding: 0.3rem 0.75rem;
}

.franklin-content .publication h3 {
  font-family: "Fraunces", Georgia, serif;
  font-size: 1.27rem;
  font-weight: 600;
  line-height: 1.42;
  color: #102a43;
  margin: 0.15rem 0 0.5rem;
}

.franklin-content .publication-authors {
  font-size: 0.93rem;
  color: #526d82;
  margin: 0.15rem 0;
}

.franklin-content .publication-venue {
  font-size: 0.93rem;
  font-style: italic;
  color: #33556e;
  margin: 0.15rem 0 0.85rem;
}

/* 5) Link buttons */
.franklin-content a.publication-link,
.franklin-content a.publication-link:hover {
  display: inline-block;
  font-size: 0.83rem;
  font-weight: 600;
  color: #ffffff;
  text-decoration: none;
  background: var(--pub);
  border-radius: 999px;
  padding: 0.42rem 0.95rem;
  box-shadow: 0 2px 8px rgba(16, 42, 67, 0.18);
  transition: transform 0.15s ease, filter 0.15s ease;
}

.franklin-content a.publication-link:hover {
  filter: brightness(1.12);
  transform: translateY(-1px);
}

/* 6) Small screens */
@media (max-width: 560px) {
  .franklin-content .publication { padding: 1rem 1.1rem 1.1rem; }
}
</style>
~~~

# Publications

~~~
<div class="publications-intro">
  Peer-reviewed research on optimal control, hybrid and non-smooth dynamics,
  numerical methods, and mathematical biology.
</div>
~~~

## Recent preprints

~~~
<div class="publication t-conf">
  <div class="publication-meta">
    <span class="publication-year">2026</span>
    <span class="publication-type">Conference paper</span>
  </div>
  <h3>Observer synthesis and peak reduction for the SIR model with output feedback under budget-constrained interventions</h3>
  <p class="publication-authors">Co-authors: Radosław Patelski, Alain Rapaport, Denis Efimov and Rosane Ushirobira</p>
  <p class="publication-venue">To appear in the 65th IEEE Conference on Decision and Control, 2026</p>
  <a class="publication-link" href="https://hal.science/hal-05699171">Read on HAL ↗</a>
</div>
~~~

~~~
<div class="publication t-preprint">
  <div class="publication-meta">
    <span class="publication-year">2026</span>
    <span class="publication-type">Submitted manuscript</span>
  </div>
  <h3>Low-Precision Arithmetic for Solving ODEs: A Case Study in Epidemiological Modeling</h3>
  <p class="publication-authors">Co-authors: El-Mehdi El Arar and Rémi Garcia</p>
  <p class="publication-venue">Submitted, 2026</p>
  <a class="publication-link" href="https://hal.science/hal-05653284">Read on HAL ↗</a>
</div>
~~~

## Journal articles

~~~
<div class="publication">
  <div class="publication-meta">
    <span class="publication-year">2026</span>
    <span class="publication-type">Journal article</span>
  </div>
  <h3>Regularization of optimal control problems on stratified domains using additional controls</h3>
  <p class="publication-authors">Co-authors: Alain Rapaport and Terence Bayen</p>
  <p class="publication-venue">SIAM Journal on Control and Optimization, Vol. 64, No. 4, pp. 2689–2714, 2026</p>
  <a class="publication-link" href="https://epubs.siam.org/doi/10.1137/25M1746896">DOI ↗</a>
</div>
~~~

~~~
<div class="publication">
  <div class="publication-meta">
    <span class="publication-year">2026</span>
    <span class="publication-type">Journal article</span>
  </div>
  <h3>On the problem of minimizing the epidemic final size for SIR model by social distancing</h3>
  <p class="publication-authors">Co-authors: Pierre-Alexandre Bliman, Patrice Loisel, Alain Rapaport and Arnaud Virelizier</p>
  <p class="publication-venue">Mathematical Biosciences and Engineering, 2026</p>
  <a class="publication-link" href="https://www.aimspress.com/article/doi/10.3934/mbe.2026022">DOI ↗</a>
</div>
~~~

~~~
<div class="publication">
  <div class="publication-meta">
    <span class="publication-year">2026</span>
    <span class="publication-type">Journal article</span>
  </div>
  <h3>Minimum Time Problem for the Double Integrator with a Loss Control Region</h3>
  <p class="publication-authors">Co-authors: Terence Bayen and Loïc Bourdin</p>
  <p class="publication-venue">Nonlinear Analysis: Hybrid Systems, 2026</p>
  <a class="publication-link" href="https://www.sciencedirect.com/science/article/abs/pii/S1751570X26000075">DOI ↗</a>
</div>
~~~

~~~
<div class="publication">
  <div class="publication-meta">
    <span class="publication-year">2025</span>
    <span class="publication-type">Journal article</span>
  </div>
  <h3>Hybrid Maximum Principle for Regional Optimal Control Problems with Non-Smooth Interfaces</h3>
  <p class="publication-authors">Co-authors: Terence Bayen and Florent Nacry</p>
  <p class="publication-venue">Journal of Convex Analysis, Vol. 32, 2025</p>
  <a class="publication-link" href="https://www.heldermann.de/JCA/JCA32/JCA321/jca32010.htm">Read article ↗</a>
</div>
~~~

~~~
<div class="publication">
  <div class="publication-meta">
    <span class="publication-year">2025</span>
    <span class="publication-type">Journal article</span>
  </div>
  <h3>On the Use of Needle-Like Perturbations in Spatially Heterogeneous Control Systems</h3>
  <p class="publication-authors">Co-authors: Terence Bayen and Loïc Bourdin</p>
  <p class="publication-venue">Journal of Optimization Theory and Applications, Vol. 204, No. 46, 2025</p>
  <a class="publication-link" href="https://link.springer.com/article/10.1007/s10957-025-02607-6">DOI ↗</a>
</div>
~~~

~~~
<div class="publication">
  <div class="publication-meta">
    <span class="publication-year">2024</span>
    <span class="publication-type">Journal article</span>
  </div>
  <h3>Loss Control Regions in Optimal Control Problems</h3>
  <p class="publication-authors">Co-authors: Terence Bayen, Loïc Bourdin and Olivier Cots</p>
  <p class="publication-venue">Journal of Differential Equations, Vol. 405, pp. 359–397, 2024</p>
  <a class="publication-link" href="https://www.sciencedirect.com/science/article/pii/S0022039624003887">DOI ↗</a>
</div>
~~~

~~~
<div class="publication">
  <div class="publication-meta">
    <span class="publication-year">2024</span>
    <span class="publication-type">Journal article</span>
  </div>
  <h3>The Hybrid Maximum Principle for Optimal Control Problems with Spatially Heterogeneous Dynamics as a Consequence of a Pontryagin Maximum Principle for L<sup>1</sup> Local Solutions</h3>
  <p class="publication-authors">Co-authors: Terence Bayen and Loïc Bourdin</p>
  <p class="publication-venue">SIAM Journal on Control and Optimization, Vol. 62, No. 4, pp. 2412–2432, 2024</p>
  <a class="publication-link" href="https://epubs.siam.org/doi/abs/10.1137/23M155311X">DOI ↗</a>
</div>
~~~

## Book chapter and conference paper

~~~
<div class="publication t-chapter">
  <div class="publication-meta">
    <span class="publication-year">2024</span>
    <span class="publication-type">Book chapter</span>
  </div>
  <h3>On the Reduction of a Spatially Hybrid Optimal Control Problem into a Temporally Hybrid Optimal Control Problem</h3>
  <p class="publication-authors">Co-authors: Terence Bayen, Loïc Bourdin and Olivier Cots</p>
  <p class="publication-venue">AIMS on Applied Mathematics, IVAN KUPKA LEGACY, Vol. 12, 2024</p>
  <a class="publication-link" href="https://www.aimsciences.org/book/AM/volume/58">Read chapter ↗</a>
</div>
~~~

~~~
<div class="publication t-conf">
  <div class="publication-meta">
    <span class="publication-year">2022</span>
    <span class="publication-type">Conference paper</span>
  </div>
  <h3>Optimal Control Problems with Non-Control Regions: Necessary Optimality Conditions</h3>
  <p class="publication-authors">Co-authors: Terence Bayen and Loïc Bourdin</p>
  <p class="publication-venue">IFAC-PapersOnLine, Vol. 55, No. 16, pp. 68–73, 2022</p>
  <a class="publication-link" href="https://www.sciencedirect.com/science/article/pii/S2405896322011739">DOI ↗</a>
</div>
~~~

## Thesis and earlier preprint

~~~
<div class="publication t-thesis">
  <div class="publication-meta">
    <span class="publication-year">2023</span>
    <span class="publication-type">Doctoral thesis</span>
  </div>
  <h3>Hybrid optimal control: optimality conditions and applications</h3>
  <p class="publication-venue">PhD thesis, Avignon Université, 2023</p>
  <a class="publication-link" href="https://theses.hal.science/tel-04335766v1">Read on HAL ↗</a>
</div>
~~~

~~~
<div class="publication t-preprint">
  <div class="publication-meta">
    <span class="publication-year">2022</span>
    <span class="publication-type">Preprint</span>
  </div>
  <h3>Hybrid Maximum Principle with Regionally Switching Parameter</h3>
  <p class="publication-authors">Co-authors: Terence Bayen and Loïc Bourdin</p>
  <a class="publication-link" href="https://univ-avignon.hal.science/hal-03638701/">Read on HAL ↗</a>
</div>
~~~
