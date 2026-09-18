@def title = "Anas Bouali"
@def tags = ["home", "academic", "landing"]
@def hascode = false

<style>
@import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Mono:wght@400;500&family=Source+Serif+4:opsz,wght@8..60,400;8..60,500;8..60,600&family=Inter:wght@400;500;600&display=swap');

:root {
  --paper: #f7f5ef;
  --ink: #17212b;
  --muted: #66717c;
  --rule: #d8d4ca;
  --accent: #9a3f2f;
}

body {
  background: var(--paper);
}

.franklin-content {
  font-family: "Inter", Arial, Helvetica, sans-serif;
  color: var(--ink);
  line-height: 1.72;
  max-width: 1120px;
  margin: 0 auto;
  padding-left: 2rem;
  padding-right: 2rem;
}

.franklin-content h1,
.franklin-content h2,
.franklin-content h3 {
  border-bottom: 0 !important;
  padding-bottom: 0 !important;
  color: var(--ink);
}

.franklin-content a {
  color: inherit;
  text-decoration-color: var(--accent);
  text-decoration-thickness: 1px;
  text-underline-offset: 4px;
}

.franklin-content a:hover {
  color: var(--accent);
}

/* ============================================================
   HERO — editorial, no card, no gradient, no rounded box
   ============================================================ */

.home-hero {
  display: grid;
  grid-template-columns: minmax(0, 1.45fr) minmax(240px, .55fr);
  gap: 4rem;
  align-items: end;
  padding: 5.5rem 0 3.5rem;
  border-bottom: 1px solid var(--ink);
}

.hero-kicker {
  font-family: "IBM Plex Mono", monospace;
  font-size: .72rem;
  letter-spacing: .11em;
  text-transform: uppercase;
  color: var(--accent);
  margin-bottom: 1.7rem;
}

.hero-name {
  font-family: "Source Serif 4", Georgia, serif !important;
  font-size: clamp(4rem, 8vw, 7rem);
  font-weight: 500;
  letter-spacing: -0.055em;
  line-height: .92;
  margin: 0 !important;
}

.hero-subtitle {
  margin-top: 2rem;
  font-family: "Source Serif 4", Georgia, serif;
  font-size: clamp(1.25rem, 2vw, 1.6rem);
  line-height: 1.45;
  max-width: 720px;
}

.hero-meta {
  border-top: 1px solid var(--rule);
  padding-top: 1rem;
}

.hero-meta-label {
  font-family: "IBM Plex Mono", monospace;
  font-size: .68rem;
  letter-spacing: .1em;
  text-transform: uppercase;
  color: var(--muted);
  margin-bottom: .7rem;
}

.hero-meta p {
  margin: 0;
  font-family: "Source Serif 4", Georgia, serif;
  font-size: 1.05rem;
  line-height: 1.55;
}

/* ============================================================
   SECTION LAYOUT
   ============================================================ */

.page-section {
  display: grid;
  grid-template-columns: 120px minmax(0, 1fr);
  gap: 3rem;
  padding: 4.3rem 0;
  border-bottom: 1px solid var(--rule);
}

.section-code {
  font-family: "IBM Plex Mono", monospace;
  font-size: .7rem;
  letter-spacing: .08em;
  color: var(--accent);
  padding-top: .45rem;
}

.section-body {
  min-width: 0;
}

.section-title {
  font-family: "Source Serif 4", Georgia, serif !important;
  font-size: clamp(2rem, 4vw, 3rem) !important;
  font-weight: 500 !important;
  letter-spacing: -0.03em !important;
  line-height: 1.08 !important;
  margin: 0 0 2rem !important;
}

.section-body > p {
  max-width: 860px;
  margin: 0;
  font-family: "Source Serif 4", Georgia, serif;
  font-size: 1.18rem;
  line-height: 1.72;
}

/* ============================================================
   POSITION / EXPERIENCE / EDUCATION
   ============================================================ */

.position-strip {
  display: grid;
  grid-template-columns: 150px minmax(0,1fr);
  gap: 2rem;
  padding-top: 1.15rem;
  border-top: 1px solid var(--ink);
}

.position-date {
  font-family: "IBM Plex Mono", monospace;
  font-size: .72rem;
  color: var(--accent);
  padding-top: .15rem;
}

.position-copy {
  max-width: 800px;
  font-family: "Source Serif 4", Georgia, serif;
  font-size: 1.12rem;
  line-height: 1.7;
}

.position-copy p {
  margin: 0;
}

.cv-list {
  border-top: 1px solid var(--ink);
}

.cv-row {
  display: grid;
  grid-template-columns: 150px minmax(250px, .9fr) minmax(260px, 1.1fr);
  gap: 2rem;
  padding: 1.35rem 0 1.45rem;
  border-bottom: 1px solid var(--rule);
}

.cv-date {
  font-family: "IBM Plex Mono", monospace;
  font-size: .72rem;
  color: var(--muted);
  padding-top: .15rem;
}

.cv-role {
  font-family: "Source Serif 4", Georgia, serif;
  font-size: 1.08rem;
  font-weight: 500;
  line-height: 1.5;
}

.cv-place {
  font-size: .92rem;
  color: var(--muted);
  line-height: 1.6;
}

.cv-place strong {
  color: var(--ink);
  font-weight: 500;
}

/* ============================================================
   RESEARCH INTERESTS
   IMPORTANT: the original bubble block below is left untouched.
   ============================================================ */

#rmap-wrap {
  margin-top: .5rem;
}

/* ============================================================
   LINKS — reference-style rather than cards
   ============================================================ */

.links-list {
  border-top: 1px solid var(--ink);
}

.links-list a {
  display: grid;
  grid-template-columns: 60px 1fr auto;
  gap: 1.25rem;
  align-items: center;
  padding: 1.15rem 0;
  border-bottom: 1px solid var(--rule);
  text-decoration: none;
  transition: padding-left .15s ease;
}

.links-list a:hover {
  padding-left: .45rem;
}

.link-index {
  font-family: "IBM Plex Mono", monospace;
  font-size: .7rem;
  color: var(--accent);
}

.link-name {
  font-family: "Source Serif 4", Georgia, serif;
  font-size: 1.12rem;
}

.link-arrow {
  font-family: "IBM Plex Mono", monospace;
  color: var(--muted);
}

@media (max-width: 820px) {
  .home-hero {
    grid-template-columns: 1fr;
    gap: 2.5rem;
    padding-top: 4rem;
  }

  .page-section {
    grid-template-columns: 1fr;
    gap: 1rem;
    padding: 3.3rem 0;
  }

  .section-code {
    padding-top: 0;
  }

  .cv-row {
    grid-template-columns: 120px 1fr;
  }

  .cv-place {
    grid-column: 2;
  }
}

@media (max-width: 560px) {
  .franklin-content {
    padding-left: 1.2rem;
    padding-right: 1.2rem;
  }

  .hero-name {
    font-size: clamp(3.5rem, 18vw, 5rem);
  }

  .position-strip {
    grid-template-columns: 1fr;
    gap: .6rem;
  }

  .cv-row {
    grid-template-columns: 1fr;
    gap: .4rem;
  }

  .cv-place {
    grid-column: auto;
  }
}
</style>

<section class="home-hero">
  <div>
    <div class="hero-kicker">Applied mathematics · Toulouse</div>
    <h1 class="hero-name">Anas Bouali</h1>
    <div class="hero-subtitle">
      Optimal control · Hybrid systems · Numerical optimisation
    </div>
  </div>

  <div class="hero-meta">
    <div class="hero-meta-label">Current position</div>
    <p>
      Temporary Teaching and Research Fellow at
      <a href="https://www.univ-toulouse.fr/" target="_blank" rel="noopener">Université de Toulouse</a>
    </p>
  </div>
</section>

<section class="page-section">
  <div class="section-code">01 / PROFILE</div>
  <div class="section-body">
    <h2 class="section-title">Research profile</h2>
    <p>
      I develop rigorous theoretical and computational tools for optimal control of hybrid and non-smooth dynamical systems.
      My work connects mathematical analysis with reliable numerical methods, with a particular focus on budget-constrained
      epidemic control and applications in mathematical biology. I am also interested in extending these approaches to robust
      optimization under uncertainty and, in the longer term, to scientific machine learning.
    </p>
  </div>
</section>

<section class="page-section">
  <div class="section-code">02 / POSITION</div>
  <div class="section-body">
    <h2 class="section-title">Current position</h2>

    <div class="position-strip">
      <div class="position-date">2026—NOW</div>
      <div class="position-copy">
        <p>
          Since September 2026, I have been a Temporary Teaching and Research Fellow (ATER) at
          <a href="https://www.univ-toulouse.fr/" target="_blank" rel="noopener">Université de Toulouse</a>.
          My work combines university teaching with research in optimal control, hybrid and non-smooth dynamical systems,
          and numerical optimisation.
        </p>
      </div>
    </div>
  </div>
</section>

<section class="page-section">
  <div class="section-code">03 / EXPERIENCE</div>
  <div class="section-body">
    <h2 class="section-title">Academic and professional experience</h2>

    <div class="cv-list">
      <div class="cv-row">
        <div class="cv-date">2026—PRESENT</div>
        <div class="cv-role">Temporary Teaching and Research Fellow</div>
        <div class="cv-place"><strong>Université de Toulouse</strong><br>France</div>
      </div>

      <div class="cv-row">
        <div class="cv-date">2024—2026</div>
        <div class="cv-role">Postdoctoral Researcher</div>
        <div class="cv-place"><strong>UMR MISTEA, INRAE Occitanie–Montpellier</strong><br>France</div>
      </div>

      <div class="cv-row">
        <div class="cv-date">2023—2024</div>
        <div class="cv-role">Temporary Teaching and Research Fellow</div>
        <div class="cv-place"><strong>Avignon Université</strong><br>France</div>
      </div>
    </div>
  </div>
</section>

<section class="page-section">
  <div class="section-code">04 / EDUCATION</div>
  <div class="section-body">
    <h2 class="section-title">Education</h2>

    <div class="cv-list">
      <div class="cv-row">
        <div class="cv-date">2020—2023</div>
        <div class="cv-role">PhD in Applied Mathematics</div>
        <div class="cv-place">
          <strong>Avignon Université</strong><br>
          Supervised by Térence Bayen and
          <a href="https://www.unilim.fr/pages_perso/loic.bourdin/" target="_blank" rel="noopener">Loïc Bourdin</a>.<br><br>
          Thesis on necessary optimality conditions and adapted numerical schemes for hybrid optimal control problems.<br><br>
          <a href="https://theses.hal.science/tel-04335766v1" target="_blank" rel="noopener">Read the thesis ↗</a>
        </div>
      </div>

      <div class="cv-row">
        <div class="cv-date">MASTER</div>
        <div class="cv-role">Master’s degree in Applied Mathematics</div>
        <div class="cv-place"><strong>Université Clermont Auvergne</strong><br>Clermont-Ferrand, France</div>
      </div>

      <div class="cv-row">
        <div class="cv-date">BACHELOR</div>
        <div class="cv-role">Bachelor’s degree in Mathematics</div>
        <div class="cv-place"><strong>Université Ibn Tofail</strong><br>Kénitra, Morocco</div>
      </div>
    </div>
  </div>
</section>

Research interests

<style>
#rmap-wrap{background:#fff radial-gradient(#edf1f7 1.2px, transparent 1.2px);background-size:22px 22px;border:1px solid #d9e2ec;border-radius:12px;padding:1.2rem 1rem .6rem;box-shadow:0 1px 2px rgba(16,42,67,.06);}
#rmap-hint{font-size:.85rem;color:#526d82;text-align:center;font-style:italic;margin:.4rem 0 .6rem;}
.rmap{width:100%;height:auto;display:block;}
.rmap .bt{font-family:"Fraunces",Georgia,serif;font-weight:600;fill:#1f2d3d;}
.rmap .kt{font-family:"Inter",Arial,sans-serif;font-weight:700;}
.rmap text{pointer-events:none;}
.rmap .halo{fill:none;stroke-width:1.5;stroke-dasharray:3 7;opacity:.45;}
.rmap .big{filter:drop-shadow(0 3px 6px rgba(16,42,67,.18));transition:stroke-width .2s ease,filter .25s ease;}
.rmap .topic{cursor:pointer;outline:none;}
.rmap .topic:hover .big,.rmap .topic:focus .big{stroke-width:5.5;filter:drop-shadow(0 8px 18px rgba(16,42,67,.30));}
.rmap .kids{pointer-events:none;}
.rmap .topic:hover .kids,.rmap .topic:focus .kids{pointer-events:auto;}
.rmap .kid circle{stroke-width:2.5;filter:drop-shadow(0 2px 5px rgba(16,42,67,.15));}
.rmap .kid{opacity:0;transform-box:fill-box;transform-origin:center;transform:scale(.4);transition:opacity .25s ease,transform .5s cubic-bezier(.2,.9,.3,1.35);}
.rmap .link{fill:none;stroke-width:2.5;stroke-linecap:round;opacity:0;stroke-dasharray:var(--len);stroke-dashoffset:var(--len);transition:stroke-dashoffset .6s ease .05s,opacity .2s ease;}
.rmap .topic:hover .kid,.rmap .topic:focus .kid{opacity:1;transform:scale(1);}
.rmap .topic:hover .link,.rmap .topic:focus .link{opacity:.9;stroke-dashoffset:0;}
@media (hover:none){.rmap .kid{opacity:1;transform:scale(1);}.rmap .link{opacity:.9;stroke-dashoffset:0;}}
</style>

<div id="rmap-wrap">
  <div id="rmap"></div>
  <noscript><div class="image-container"><img src="/assets/map.svg" alt="Research interests map"></div></noscript>
</div>

<script>
(function(){
  var NS='http://www.w3.org/2000/svg',W=1000,H=640,M=30;
  var TIER={1:{r:95,fs:24,lh:28,sw:4.5},2:{r:84,fs:22,lh:26,sw:4},3:{r:70,fs:19,lh:23,sw:3.5}};
  var DATA=[
    {name:'Optimal Control',t:1,color:'#2b3eb5',light:'#4c6ef5',tint:'#edf2ff',kfill:'#f5f8ff',x:300,y:200,
     kids:[{n:'Hybrid Systems',x:105,y:170},{n:'Loss Control Regions',x:170,y:82},
           {n:'Pontryagin Maximum Principle',x:430,y:82},{n:'Optimal Synthesis',x:560,y:160},
           {n:'Feedback Controls',x:470,y:270}]},
    {name:'Numerical Optimization',t:2,color:'#e03131',light:'#fa5252',tint:'#fff0f0',kfill:'#fff7f7',x:740,y:170,
     kids:[{n:'Shooting Methods',x:620,y:270},{n:'Regularization Schemes',x:880,y:90}]},
    {name:'Modelling',t:3,color:'#2f9e44',light:'#51cf66',tint:'#eefbee',kfill:'#f6fdf6',x:540,y:390,
     kids:[{n:'Resources Allocation',x:700,y:360},{n:'Epidemiology',x:565,y:530}]},
    {name:'State Estimation',t:3,color:'#f08c00',light:'#ffa94d',tint:'#fff5e6',kfill:'#fffaf2',x:270,y:500,
     kids:[{n:'KKL Observer',x:95,y:430},{n:'Extended Kalman Filter',x:140,y:555}]},
    {name:'Scientific Computing',t:3,color:'#0c8599',light:'#22b8cf',tint:'#e6f7fa',kfill:'#f2fbfd',x:810,y:470,
     kids:[{n:'Stochastic Rounding',x:920,y:350}]}
  ];
  var host=document.getElementById('rmap'); if(!host)return;
  var svg=document.createElementNS(NS,'svg');
  svg.setAttribute('viewBox','0 0 '+W+' '+H); svg.setAttribute('class','rmap');
  host.appendChild(svg);
  var defs=document.createElementNS(NS,'defs'); svg.appendChild(defs);

  function el(n,at,p){var e=document.createElementNS(NS,n);for(var k in at)e.setAttribute(k,at[k]);(p||svg).appendChild(e);return e;}
  function wrap(s,m){var w=s.split(' '),L=[],c='';for(var i=0;i<w.length;i++){var t=(c?c+' ':'')+w[i];if(t.length>m&&c){L.push(c);c=w[i];}else c=t;}if(c)L.push(c);return L;}
  function label(L,x,y,cls,lh,fs,fill){var t=el('text',{x:x,y:y,'text-anchor':'middle','class':cls});t.style.fontSize=fs+'px';if(fill)t.style.fill=fill;var y0=y-(L.length-1)*lh/2;for(var i=0;i<L.length;i++){var ts=el('tspan',{x:x,y:y0+i*lh},t);ts.textContent=L[i];}return t;}

  DATA.forEach(function(tp){
    var T=TIER[tp.t], bl=wrap(tp.name,12);
    var tmp=label(bl,tp.x,tp.y,'bt',T.lh,T.fs), bb=tmp.getBBox(); tmp.remove();
    tp.Rb=Math.max(bb.width/2+18, bb.height/2+18, T.r);
  });

  DATA.forEach(function(tp,idx){
    var T=TIER[tp.t];
    var grad=el('radialGradient',{id:'rg'+idx,cx:'35%',cy:'30%',r:'80%'},defs);
    el('stop',{offset:'0%','stop-color':'#ffffff'},grad);
    el('stop',{offset:'100%','stop-color':tp.tint},grad);

    var g=el('g',{'class':'topic',tabindex:'0'});
    var kids=tp.kids.map(function(kd,i){
      var kl=wrap(kd.n,13);
      var kt=label(kl,tp.x,tp.y,'kt',16,13), kb=kt.getBBox(); kt.remove();
      var rk=Math.max(46,Math.max(kb.width/2,kb.height/2)+14);
      var x=kd.x,y=kd.y,dx=x-tp.x,dy=y-tp.y,d=Math.sqrt(dx*dx+dy*dy)||1;
      var min=tp.Rb+rk+18;
      if(d<min){x=tp.x+dx/d*min;y=tp.y+dy/d*min;}
      x=Math.max(M+rk,Math.min(W-M-rk,x)); y=Math.max(M+rk,Math.min(H-M-rk,y));
      return {L:kl,i:i,r:rk,x:x,y:y};
    });

    var kg=el('g',{'class':'kids'},g);
    kids.forEach(function(kd){
      var mx=(tp.x+kd.x)/2,my=(tp.y+kd.y)/2,dx=kd.x-tp.x,dy=kd.y-tp.y,d=Math.sqrt(dx*dx+dy*dy)||1;
      var p=el('path',{d:'M'+tp.x+' '+tp.y+' Q'+(mx-dy/d*d*0.15)+' '+(my+dx/d*d*0.15)+' '+kd.x+' '+kd.y,'class':'link',stroke:tp.light},kg);
      p.style.setProperty('--len',p.getTotalLength());
      p.style.transitionDelay=(kd.i*60)+'ms';
      var kgg=el('g',{'class':'kid'},kg); kgg.style.transitionDelay=(kd.i*60)+'ms';
      el('circle',{cx:kd.x,cy:kd.y,r:kd.r,stroke:tp.light,fill:tp.kfill},kgg);
      kgg.appendChild(label(kd.L,kd.x,kd.y,'kt',16,13,tp.color));
    });

    el('circle',{cx:tp.x,cy:tp.y,r:tp.Rb+7,'class':'halo',stroke:tp.light},g);
    var big=el('circle',{cx:tp.x,cy:tp.y,r:tp.Rb,'class':'big',stroke:tp.color,fill:'url(#rg'+idx+')'},g);
    big.style.strokeWidth=T.sw+'px';
    g.appendChild(label(wrap(tp.name,12),tp.x,tp.y,'bt',T.lh,T.fs));
  });
})();
</script>

Links

<section class="page-section">
  <div class="section-code">06 / LINKS</div>
  <div class="section-body">
    <h2 class="section-title">Links</h2>

    <div class="links-list">
      <a href="mailto:anas.bouali@outlook.com">
        <span class="link-index">[01]</span>
        <span class="link-name">Email</span>
        <span class="link-arrow">↗</span>
      </a>

      <a href="https://scholar.google.com/citations?user=CdSC_JsAAAAJ&hl=fr" target="_blank" rel="noopener">
        <span class="link-index">[02]</span>
        <span class="link-name">Google Scholar</span>
        <span class="link-arrow">↗</span>
      </a>

      <a href="https://github.com/AnasXbouali" target="_blank" rel="noopener">
        <span class="link-index">[03]</span>
        <span class="link-name">GitHub</span>
        <span class="link-arrow">↗</span>
      </a>

      <a href="https://www.linkedin.com/in/anas-bouali-276539215/" target="_blank" rel="noopener">
        <span class="link-index">[04]</span>
        <span class="link-name">LinkedIn</span>
        <span class="link-arrow">↗</span>
      </a>
    </div>
  </div>
</section>
