+++
title = "Teaching and Supervision | Anas Bouali"
hascode = false
rss = "Details of teaching experience and student supervision by Anas Bouali."
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
  background: #A85741; /* Oxblood Accent */
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
  --accent: #A85741; /* Oxblood */
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
  --accent: #6B4C5A; /* Plum */
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
  color: #4A6B7C; /* Slate */
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

# Teaching and supervision

## Teaching experience

~~~
<div class="teaching-position">
  <h3 class="position-title">Temporary Teaching and Research Assistant (ATER)</h3>
  <p class="position-meta"><strong>Université de Toulouse</strong> · 2026–2027</p>
  
  <div class="course">
    <h4 class="course-title">Analysis 2</h4>
    <p class="course-meta">Second-year BSc Mathematics · Integration and Numerical Series</p>
  </div>
  
  <div class="course">
    <h4 class="course-title">Introduction to Statistics and Introduction to R</h4>
    <p class="course-meta">Second-year BSc Mathematics</p>
  </div>
  
  <div class="course">
    <h4 class="course-title">Numerical Methods</h4>
    <p class="course-meta">Third-year BSc Mathematics</p>
  </div>
</div>
~~~

~~~
<div class="teaching-position">
  <h3 class="position-title">Temporary Teaching and Research Assistant (ATER)</h3>
  <p class="position-meta"><strong>Avignon Université</strong> · 2023–2024</p>
  
  <div class="course">
    <h4 class="course-title">Analysis 1</h4>
    <p class="course-meta">First-year BSc Mathematics and Computer Science · 33 hours</p>
    <div class="course-content">
      <ul>
        <li>Elementary functions and their properties</li>
        <li>Differentiation and integration</li>
        <li>Linear differential equations</li>
      </ul>
    </div>
  </div>
  
  <div class="course">
    <h4 class="course-title">Analysis 2</h4>
    <p class="course-meta">First-year BSc Mathematics and Computer Science · 21 hours</p>
    <div class="course-content">
      <ul>
        <li>Sequences of real numbers and limits</li>
        <li>Fundamental theorems on sequences</li>
        <li>Asymptotic behaviour and complex sequences</li>
      </ul>
    </div>
  </div>
  
  <div class="course">
    <h4 class="course-title">Algebra 1</h4>
    <p class="course-meta">First-year BSc Mathematics and Computer Science · 27 hours</p>
    <div class="course-content">
      <ul>
        <li>Introduction to logic and set theory</li>
        <li>Arithmetic and trigonometry</li>
        <li>Complex numbers</li>
      </ul>
    </div>
  </div>
  
  <div class="course">
    <h4 class="course-title">Algebra 2</h4>
    <p class="course-meta">First-year BSc Mathematics and Computer Science · 21 hours</p>
    <div class="course-content">
      <ul>
        <li>Linear systems and matrices</li>
        <li>Vector subspaces</li>
        <li>Linear maps and determinants</li>
      </ul>
    </div>
  </div>
  
  <div class="course">
    <h4 class="course-title">Mathematics</h4>
    <p class="course-meta">First-year BSc Life and Earth Sciences · 9 hours</p>
    <div class="course-content">
      <ul>
        <li>Study of functions</li>
        <li>Differentiation and integration</li>
      </ul>
    </div>
  </div>
</div>
~~~

~~~
<div class="teaching-position">
  <h3 class="position-title">PhD Teaching Fellow</h3>
  <p class="position-meta"><strong>Avignon Université</strong> · 2020–2023</p>
  
  <div class="course">
    <h4 class="course-title">Algebra 1</h4>
    <p class="course-meta">First-year BSc Mathematics · 27 hours</p>
    <div class="course-content">
      <ul>
        <li>Introduction to logic and set theory</li>
        <li>Arithmetic and trigonometry</li>
        <li>Complex numbers</li>
      </ul>
    </div>
  </div>
  
  <div class="course">
    <h4 class="course-title">Algebra 2</h4>
    <p class="course-meta">First-year BSc Mathematics · 21 hours</p>
    <div class="course-content">
      <ul>
        <li>Linear systems and matrices</li>
        <li>Vector subspaces</li>
        <li>Linear maps and determinants</li>
      </ul>
    </div>
  </div>
  
  <div class="course">
    <h4 class="course-title">Mathematics</h4>
    <p class="course-meta">First-year BSc Life and Earth Sciences · 9 hours</p>
    <div class="course-content">
      <ul>
        <li>Study of functions</li>
        <li>Differentiation and integration</li>
      </ul>
    </div>
  </div>
</div>
~~~

## Student supervision

~~~
<div class="supervision-item">
  <span class="supervision-type">First-year Master's Internship</span>
  <span class="supervision-year">2026</span>
  <h4 class="supervision-topic">Topic: <em>Numerical methods for non-smooth optimal control problems</em></h4>
  <p class="supervision-details">Co-supervised with Olivier Cots, Université de Toulouse.</p>
</div>
~~~

~~~
<div class="supervision-item">
  <span class="supervision-type">Second-year Master's Internship</span>
  <span class="supervision-year">2026</span>
  <h4 class="supervision-topic">Topic: <em>Optimal control in the epidemiology of vector-borne diseases</em></h4>
  <p class="supervision-details">Co-supervised with Alain Rapaport and Patrice Loisel, UMR MISTEA, Centre INRAE Occitanie-Montpellier.</p>
</div>
~~~

~~~
<div class="supervision-item">
  <span class="supervision-type">Second-year Master's Internship</span>
  <span class="supervision-year">2025</span>
  <h4 class="supervision-topic">Topic: <em>Optimal control in epidemiology with variant emergence</em></h4>
  <p class="supervision-details">Co-supervised with Alain Rapaport and Patrice Loisel, UMR MISTEA, Centre INRAE Occitanie-Montpellier.</p>
</div>
~~~
