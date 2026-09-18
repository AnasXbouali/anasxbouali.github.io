@def title = "Anas Bouali"
@def tags = ["home", "academic", "landing"]
@def hascode = false

<style>
@import url('https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,500;9..144,600;9..144,700&family=Inter:wght@400;500;600;700&family=IBM+Plex+Mono:wght@400;500&display=swap');

/* ============================================================
   Homepage redesign
   Keep the existing HTML structure and the research-bubble block.
   ============================================================ */

:root {
  --paper: #fbfaf7;
  --ink: #17212b;
  --muted: #68717a;
  --rule: #d8d5ce;
  --accent: #9b3f32;
}

body {
  background: var(--paper);
}

.franklin-content {
  font-family: "Inter", Arial, Helvetica, sans-serif;
  color: var(--ink);
  line-height: 1.72;
  counter-reset: home-section;
}

/* ------------------------------------------------------------
   Headings: editorial numbering instead of colored side bars
   ------------------------------------------------------------ */

.franklin-content h1,
.franklin-content h2,
.franklin-content h3 {
  border-bottom: 0 !important;
  padding-bottom: 0 !important;
  color: var(--ink);
}

.franklin-content h2 {
  counter-increment: home-section;
  display: grid;
  grid-template-columns: 3rem minmax(0, 1fr);
  align-items: baseline;
  column-gap: 0.8rem;

  font-family: "Fraunces", Georgia, "Times New Roman", serif;
  font-size: 1.85rem;
  font-weight: 600;
  letter-spacing: -0.025em;
  line-height: 1.15;

  margin: 4.8rem 0 1.7rem;
  padding: 0 !important;
  border-left: 0 !important;
}

.franklin-content h2::before {
  content: "0" counter(home-section);
  font-family: "IBM Plex Mono", monospace;
  font-size: 0.68rem;
  font-weight: 500;
  letter-spacing: 0.06em;
  color: var(--accent);
}

/* ------------------------------------------------------------
   Hero: no card, no gradient, no rounded container
   ------------------------------------------------------------ */

.franklin-content .hero-banner {
  position: relative;
  background: transparent;
  border: 0;
  border-top: 1px solid var(--ink);
  border-bottom: 1px solid var(--ink);
  border-radius: 0;
  box-shadow: none;

  padding: 4.4rem 0 3.4rem;
  margin: 3.2rem 0 0;
  text-align: left;
}

.franklin-content .hero-banner::before {
  content: "APPLIED MATHEMATICS · TOULOUSE";
  display: block;
  margin-bottom: 1.5rem;

  font-family: "IBM Plex Mono", monospace;
  font-size: 0.68rem;
  font-weight: 500;
  letter-spacing: 0.11em;
  color: var(--accent);
}

.franklin-content .hero-name {
  font-family: "Fraunces", Georgia, serif;
  font-size: clamp(3.7rem, 8vw, 6.7rem);
  font-weight: 600;
  color: var(--ink);

  margin: 0 0 1.45rem 0;
  letter-spacing: -0.055em;
  line-height: 0.95;
}

.franklin-content .hero-role {
  max-width: 760px;
  font-family: "Fraunces", Georgia, serif;
  font-size: clamp(1.12rem, 2vw, 1.42rem);
  color: #2f3942;
  margin: 0;
  line-height: 1.55;
}

.franklin-content .hero-role a {
  color: inherit;
  font-weight: 600;
  text-decoration: underline;
  text-decoration-color: var(--accent);
  text-decoration-thickness: 1px;
  text-underline-offset: 4px;
  border: 0;
}

.franklin-content .hero-role a:hover {
  color: var(--accent);
  background: transparent;
  padding: 0;
}

/* ------------------------------------------------------------
   Normal text / links
   ------------------------------------------------------------ */

.franklin-content > p {
  max-width: 850px;
  font-family: "Fraunces", Georgia, serif;
  font-size: 1.08rem;
  line-height: 1.8;
}

.franklin-content a {
  text-underline-offset: 4px;
}

/* ------------------------------------------------------------
   Former "cards": flatten into document / CV rows
   ------------------------------------------------------------ */

.franklin-content .info-card {
  background: transparent;
  border: 0;
  border-top: 1px solid var(--ink);
  border-radius: 0;
  padding: 0;
  margin-bottom: 0;
  box-shadow: none;
  transition: none;
}

.franklin-content .info-card:hover {
  transform: none;
  box-shadow: none;
}

.franklin-content .info-card p {
  margin: 0;
  padding: 1.15rem 0 1.2rem;
  border-bottom: 1px solid var(--rule);

  font-size: 0.98rem;
  line-height: 1.7;
  color: #34414b;
}

.franklin-content .info-card p:last-child {
  margin-bottom: 0;
}

.franklin-content .info-card strong {
  display: inline-block;
  min-width: 9.5rem;

  font-family: "IBM Plex Mono", monospace;
  font-size: 0.78rem;
  font-weight: 500;
  letter-spacing: -0.01em;
  color: var(--ink);
}

.franklin-content .info-card a {
  color: inherit;
  font-weight: 600;
  text-decoration: underline;
  text-decoration-color: var(--accent);
  text-decoration-thickness: 1px;
  text-underline-offset: 4px;
  border: 0;
}

.franklin-content .info-card a:hover {
  color: var(--accent);
  background: transparent;
  padding: 0;
}

/* ------------------------------------------------------------
   Noscript research image fallback only.
   The animated research-bubble section itself is NOT restyled here.
   ------------------------------------------------------------ */

.franklin-content .image-container {
  background: transparent;
  border: 0;
  border-radius: 0;
  padding: 0;
  box-shadow: none;
  text-align: center;
}

.franklin-content .image-container img {
  width: 100%;
  max-width: 900px;
  height: auto;
  padding: 0;
  margin: 0 auto;
  display: block;
  border-radius: 0;
  box-sizing: border-box;
  object-fit: contain;
}

/* ------------------------------------------------------------
   Links: bibliography / reference-list feel, not app cards
   ------------------------------------------------------------ */

.franklin-content .link-grid {
  display: block;
  margin-top: 0;
  border-top: 1px solid var(--ink);
}

.franklin-content .link-card {
  position: relative;
  display: grid;
  grid-template-columns: 2rem 1fr auto;
  align-items: center;
  gap: 0.8rem;

  background: transparent;
  border: 0;
  border-bottom: 1px solid var(--rule);
  border-radius: 0;
  padding: 1rem 0;

  text-decoration: none;
  color: var(--ink);
  font-family: "Fraunces", Georgia, serif;
  font-weight: 500;
  font-size: 1.08rem;

  box-shadow: none;
  transition: padding-left 0.16s ease, color 0.16s ease;
}

.franklin-content .link-card::after {
  content: "↗";
  font-family: "IBM Plex Mono", monospace;
  font-size: 0.76rem;
  color: var(--muted);
}

.franklin-content .link-card:hover {
  transform: none;
  box-shadow: none;
  border-color: var(--rule);
  color: var(--accent);
  padding-left: 0.4rem;
}

.franklin-content .link-icon {
  display: inline-flex;
  align-items: center;
  justify-content: flex-start;
  width: 18px;
  height: 18px;
  color: var(--accent);
  transition: none;
}

.franklin-content .link-card:hover .link-icon {
  color: var(--accent);
  transform: none;
}

.franklin-content .link-icon svg {
  width: 100%;
  height: 100%;
  display: block;
}

/* ------------------------------------------------------------
   Responsive
   ------------------------------------------------------------ */

@media (max-width: 700px) {
  .franklin-content .hero-banner {
    padding: 3rem 0 2.6rem;
    margin-top: 2rem;
  }

  .franklin-content h2 {
    grid-template-columns: 2.2rem minmax(0, 1fr);
    margin-top: 3.7rem;
  }

  .franklin-content .info-card strong {
    display: block;
    min-width: 0;
    margin-bottom: 0.35rem;
  }
}
</style>

<div class="hero-banner">
  <h1 class="hero-name">Anas Bouali</h1>
  <p class="hero-role">
    Optimal control · Hybrid systems · Numerical optimisation<br>
    Temporary Teaching and Research Fellow at 
    <a href="https://www.univ-toulouse.fr/" target="_blank" rel="noopener">Université de Toulouse</a>
  </p>
</div>

Research profile

I develop rigorous theoretical and computational tools for optimal control of hybrid and non-smooth dynamical systems. My work connects mathematical analysis with reliable numerical methods, with a particular focus on budget-constrained epidemic control and applications in mathematical biology. I am also interested in extending these approaches to robust optimization under uncertainty and, in the longer term, to scientific machine learning.

Current position

<div class="info-card">
  <p>
    Since September 2026, I have been a Temporary Teaching and Research Fellow (ATER) at
    <a href="https://www.univ-toulouse.fr/" target="_blank" rel="noopener">Université de Toulouse</a>.
    My work combines university teaching with research in optimal control, hybrid and non-smooth dynamical systems, and numerical optimisation.
  </p>
</div>

Academic and professional experience

<div class="info-card">
  <p>
    <strong>2026–present:</strong> Temporary Teaching and Research Fellow, Université de Toulouse (France).
  </p>
  <p>
    <strong>2024–2026:</strong> Postdoctoral Researcher, UMR MISTEA, INRAE Occitanie–Montpellier (France).
  </p>
  <p>
    <strong>2023–2024:</strong> Temporary Teaching and Research Fellow, Avignon Université (France).
  </p>
</div>

Education

<div class="info-card">
  <p>
    <strong>2020–2023:</strong> PhD in Applied Mathematics, Avignon Université, supervised by Térence Bayen and
    <a href="https://www.unilim.fr/pages_perso/loic.bourdin/" target="_blank" rel="noopener">Loïc Bourdin</a>.
    My thesis focused on necessary optimality conditions and adapted numerical schemes for hybrid optimal control problems.
    <a href="https://theses.hal.science/tel-04335766v1" target="_blank" rel="noopener">Read the thesis</a>.
  </p>
  <p>
    <strong>Master’s degree:</strong> Master’s degree in Applied Mathematics, Université Clermont Auvergne, Clermont-Ferrand (France).
  </p>
  <p>
    <strong>Bachelor’s degree:</strong> Bachelor’s degree in Mathematics, Université Ibn Tofail, Kénitra (Morocco).
  </p>
</div>

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
</div>
