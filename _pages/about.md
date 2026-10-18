---
permalink: /
title: ""
excerpt: ""
author_profile: false
layout: single
redirect_from:
  - /about/
  - /about.html
---

<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=IBM+Plex+Mono:wght@400;500&family=IBM+Plex+Sans:wght@400;500;600&family=Spectral:ital,wght@0,400;0,500;0,600;1,400&display=swap">

<style>
/* ---------- Force the whole page (nav bar + footer too) into dark mode ---------- */
html, html[data-theme="dark"]{
  --global-bg-color:#121315 !important;
  --global-footer-bg-color:#0c0d0e !important;
  --global-text-color:#e4e6e8 !important;
  --global-text-color-light:#9aa1a9 !important;
  --global-border-color:#2a2d31 !important;
  --global-dark-border-color:#2a2d31 !important;
  --global-link-color:#8fb8e0 !important;
  --global-link-color-hover:#b9d4ee !important;
  --global-link-color-visited:#8fb8e0 !important;
  --global-masthead-link-color:#c9cdd2 !important;
  --global-masthead-link-color-hover:#ffffff !important;
  --global-base-color:#8fb8e0 !important;
}
html, body{ background:#121315 !important; }
.masthead{ border-bottom:1px solid #2a2d31; }
.page__footer{ background:#0c0d0e !important; border-top:1px solid #2a2d31; }
.page__footer, .page__footer a{ color:#7d848c !important; }


/* ---------- Replace the theme's top nav with a custom bar on this page ---------- */
.masthead{ display:none !important; }
body{ padding-top:0 !important; }
#main{ max-width:none !important; margin-top:0 !important; padding:0 !important; animation:none !important; }
.page{ width:100% !important; float:none !important; margin:0 !important; padding:0 !important; }
.page__inner-wrap, .page__content{ width:100% !important; float:none !important; }
.page__meta{ display:none !important; }

.jm-bar{ background:#1c1f23; border-bottom:1px solid #2a2d31; margin:0 0 2.4rem; }
.jm-bar-in{ max-width:72rem; margin:0 auto; padding:.9rem 1.5rem; display:flex; align-items:center; gap:2rem; }
.jm-bar .jm-brand{ font-family:'IBM Plex Sans',system-ui,sans-serif; font-weight:600; font-size:2rem; color:#f0a63a !important;
  text-decoration:none !important; border:0 !important; white-space:nowrap; letter-spacing:-.01em; }
.jm-pills{ display:flex; flex-wrap:wrap; gap:.7rem; flex:1; }
.jm-pills a{ font-family:'IBM Plex Sans',system-ui,sans-serif; font-size:1rem; color:#8fb8e0 !important; text-decoration:none !important;
  border:1px solid rgba(143,184,224,.35) !important; border-radius:999px; padding:.3rem 1rem; transition:all .15s; }
.jm-pills a:hover{ border-color:#8fb8e0 !important; background:rgba(143,184,224,.08); }
.jm-pills a.on{ color:#f0a63a !important; border-color:rgba(240,166,58,.55) !important; }
.jm-bar .jm-toy{ margin-left:auto; }
@media (max-width:680px){
  .jm-bar-in{ flex-wrap:wrap; gap:.8rem; padding:.9rem 1rem; }
  .jm-bar .jm-brand{ font-size:1.6rem; }
  .jm-pills{ gap:.5rem; }
  .jm-pills a{ font-size:.9rem; padding:.25rem .8rem; }
  .jm-bar .jm-toy{ display:none; }
}

/* ---------- Homepage ---------- */
.jm{
  --ink:#e4e6e8; --soft:#9aa1a9; --faint:#6b7279;
  --line:#2a2d31; --card:#1a1c1f; --card-hi:#202327;
  --accent:#8fb8e0;
  --attack:#d4797c; --epi:#7fa7d1; --narr:#76b5a3;
  --serif:'Spectral',Georgia,serif;
  --sans:'IBM Plex Sans',system-ui,-apple-system,sans-serif;
  --mono:'IBM Plex Mono',ui-monospace,monospace;
  max-width:46rem; margin:0 auto; padding:0 1rem; color:var(--ink);
  font-family:var(--sans); font-size:1rem; line-height:1.65;
}
.jm a{ color:var(--accent); text-decoration:none; border-bottom:1px solid transparent; }
.jm a:hover{ border-bottom-color:var(--accent); }

/* header */
.jm-head h1{ font-family:var(--serif); font-weight:500; font-size:2.6rem; line-height:1.1; margin:0; color:var(--ink); }
.jm-nav{ margin:.9rem 0 0; display:flex; flex-wrap:wrap; gap:.4rem 1.4rem; font-family:var(--mono); font-size:.85rem; }
.jm-nav a{ color:var(--soft); }
.jm-nav a:hover{ color:var(--ink); border-bottom-color:var(--ink); }

/* sections */
.jm section{ padding:2.6rem 0 0; scroll-margin-top:20px; }
.jm h2{ font-family:var(--mono); font-weight:500; font-size:.8rem; letter-spacing:.14em; text-transform:uppercase;
  color:var(--faint); margin:0 0 1.2rem; padding:0 0 .6rem; border-bottom:1px solid var(--line); }


/* header with photo + icon links */

.jm-id{ display:grid; grid-template-columns:170px 1fr; gap:1.8rem; align-items:center; }
.jm-id img{ width:170px; height:170px; object-fit:cover; border-radius:50%; display:block; border:2px solid var(--line); }
.jm-tag{ font-size:1.02rem; color:var(--soft); margin:.5rem 0 0; max-width:24rem; line-height:1.5; }
.jm-icons{ list-style:none; margin:1rem 0 0; padding:0; font-size:.95rem; }
.jm-icons li{ margin:0 0 .35rem; padding:0; color:var(--soft); display:flex; align-items:center; }
.jm-icons i{ width:1.6rem; color:var(--soft); font-size:1rem; text-align:left; }
.jm-icons a{ color:var(--soft); }
.jm-icons a:hover{ color:var(--ink); border-bottom-color:var(--ink); }

/* shield toy */
.jm-toy{ text-align:center; user-select:none; }
.jm-toy span{ display:block; font-family:'IBM Plex Sans',system-ui,sans-serif; font-size:.85rem; color:#8fb8e0; margin:0 0 .35rem; white-space:nowrap; }
.jm-toy canvas{ cursor:pointer; display:block; margin:0 auto; }

/* bio */
.jm-bio{ display:grid; grid-template-columns:180px 1fr; gap:1.8rem; align-items:start; }
.jm-bio img{ width:180px; height:180px; object-fit:cover; border-radius:6px; display:block; }
.jm-bio p{ margin:0 0 .9rem; }
.jm-lede{ font-family:var(--serif); font-size:1.2rem; line-height:1.5; color:var(--ink); }
.jm-lede em{ color:var(--accent); }
.jm-social{ margin:1.2rem 0 0; font-family:var(--mono); font-size:.85rem; color:var(--faint); }
.jm-social a{ color:var(--soft); }
.jm-social a:hover{ color:var(--ink); border-bottom-color:var(--ink); }
.jm-social .dot{ margin:0 .5rem; }


/* research agenda */
.jm-agenda-lede{ color:var(--soft); margin:0 0 1.4rem; font-size:1rem; }
.jm-agenda-title{ font-family:var(--serif); font-weight:500; font-size:1.6rem; line-height:1.25; color:var(--ink); margin:0 0 .6rem; }
.jm-pillars{ display:grid; grid-template-columns:repeat(2,1fr); gap:1rem; }
.jm-pillar{ background:var(--card); border:1px solid var(--line); border-top:3px solid var(--epi); border-radius:6px; padding:1.1rem 1.15rem 1.2rem; display:flex; flex-direction:column; }
.jm-pillar.i{ border-top-color:var(--narr); }
.jm-pillar.d{ border-top-color:var(--epi); }
.jm-pillar.x{ border-top-color:#f0a63a; }
.jm-pillar.g{ border-top-color:#b49be0; }
.jm-pillar .num{ font-family:var(--mono); font-size:.75rem; letter-spacing:.14em; text-transform:uppercase; }
.jm-pillar.i .num{ color:var(--narr); } .jm-pillar.d .num{ color:var(--epi); } .jm-pillar.x .num{ color:#f0a63a; } .jm-pillar.g .num{ color:#b49be0; }
.jm-pillar h3{ font-family:var(--serif); font-weight:500; font-size:1.12rem; line-height:1.3; color:var(--ink); margin:.45rem 0 .55rem; }
.jm-pillar p{ margin:0; color:#c3c8cd; font-size:.9rem; line-height:1.55; flex:1; }
.jm-tags{ margin:.9rem 0 0; display:flex; flex-wrap:wrap; gap:.4rem; }
.jm-tags a, .jm-tags span{ font-family:var(--mono); font-size:.72rem; color:var(--soft) !important; border:1px solid var(--line) !important; border-radius:4px; padding:.15rem .5rem; }
.jm-tags a:hover{ color:var(--ink) !important; border-color:var(--soft) !important; }
@media (max-width:680px){ .jm-pillars{ grid-template-columns:1fr; } }

/* projects */
.jm-proj{ background:var(--card); border:1px solid var(--line); border-left:3px solid var(--epi);
  border-radius:6px; padding:1.2rem 1.4rem; margin:0 0 1rem; transition:background .15s; }
.jm-proj:hover{ background:var(--card-hi); }
.jm-proj.attack{ border-left-color:var(--attack); }
.jm-proj.narr{ border-left-color:var(--narr); }
.jm-proj h3{ font-family:var(--serif); font-weight:500; font-size:1.3rem; margin:0; color:var(--ink); }
.jm-proj .who{ font-size:.85rem; color:var(--faint); margin:.2rem 0 .6rem; font-family:var(--mono); }
.jm-proj p{ margin:0; color:#c3c8cd; font-size:.95rem; }
.jm-proj .links{ margin:.8rem 0 0; font-family:var(--mono); font-size:.82rem; color:var(--faint); }
.jm-proj .links .dot{ margin:0 .45rem; }

/* writing */
.jm-pubs{ list-style:none; margin:0; padding:0; }
.jm-pubs li{ margin:0 0 1.3rem; padding:0; }
.jm-pubs .t{ font-family:var(--serif); font-size:1.12rem; color:var(--ink); display:block; }
.jm-pubs .a{ font-size:.9rem; color:var(--soft); display:block; margin:.15rem 0 0; }
.jm-pubs .a b{ color:var(--ink); font-weight:600; }
.jm-pubs .v{ font-size:.9rem; color:var(--faint); font-style:italic; }
.jm-pubs .l{ font-family:var(--mono); font-size:.8rem; margin-left:.4rem; }

/* news */
.jm-news{ list-style:none; margin:0; padding:0; }
.jm-news li{ display:grid; grid-template-columns:4rem 1fr; gap:1rem; margin:0 0 .7rem; font-size:.95rem; color:#c3c8cd; }
.jm-news .y{ font-family:var(--mono); font-size:.85rem; color:var(--faint); padding-top:.1rem; }

.jm-end{ text-align:center; color:var(--faint); font-family:var(--mono); font-size:.8rem; padding:3rem 0 1rem; }

@media (max-width:680px){
  .jm-head h1{ font-size:2.1rem; }
  .jm-bio{ grid-template-columns:1fr; gap:1.2rem; }
  .jm-bio img{ width:140px; height:140px; }
}
</style>

<div class="jm-bar" markdown="0">
  <div class="jm-bar-in">
    <a class="jm-brand" href="/">Jack Moody</a>
    <nav class="jm-pills">
      <a href="#bio" class="on">Bio</a>
      <a href="#research">Research</a>
      <a href="#publications">Publications</a>
      <a href="#projects">Projects</a>
      <a href="#news">News</a>
      <a href="/cv/">CV</a>
    </nav>
    <div class="jm-toy">
      <span>Click me (for fun)</span>
      <canvas id="jm-shield" width="96" height="110" aria-label="Bouncing ball inside a shield"></canvas>
    </div>
  </div>
</div>

<div class="jm" markdown="0">

  <section id="bio" style="padding-top:0">
    <h2>Bio</h2>
    <div class="jm-bio">
      <img src="/images/profile.jpeg" alt="Jack Moody">
      <div>
        <p class="jm-lede">Adversaries and crowds both leave noisy, shifting traces. I build models that turn them into <em>calibrated, verifiable evidence</em>: signals a decision-maker can trust.</p>
        <p>I'm a U.S. Army officer working in defensive cyber operations. I'm currently a senior project manager leading a 170-person organization that supports cyber defense missions worldwide, and a Data Scientist IV, one of six people qualified at that level across the Department of Defense, where I build machine-learning and analytic pipelines that find malicious activity in host and network data. Previously I was project lead and AI engineer for the Cyber National Mission Force AI Task Force, developing LLM and ML tools for threat hunting, and led a 20-person incident response team countering nation-state activity against critical infrastructure.</p>
        <p>My research spans adversarial machine learning, statistical network science, and uncertainty quantification, applied to cyber telemetry and online influence operations. I hold an M.S. in Applied &amp; Computational Mathematics from Johns Hopkins and a B.S. in Physics from UMass Amherst, and I'm completing an M.S. in Computer Science at CU Boulder. I'm also a graduate teaching assistant at Hopkins for stochastic differential equations and partial differential equations.</p>
        <div class="jm-social">
          <a href="mailto:jackdmoody@pm.me">Email</a><span class="dot">•</span>
          <a href="https://scholar.google.com/citations?user=KzcqBo8AAAAJ">Google Scholar</a><span class="dot">•</span>
          <a href="https://github.com/jackdmoody">GitHub</a><span class="dot">•</span>
          <a href="https://www.linkedin.com/in/jack-moody">LinkedIn</a><span class="dot">•</span>
          <a href="/cv/">CV</a>
        </div>
      </div>
    </div>
  </section>

  <section id="research">
    <h2>Research Agenda</h2>
    <p class="jm-agenda-title">Identify, Detect, Decide, and Delegate Under Adversarial Contamination</p>
    <p class="jm-agenda-lede">Cyber telemetry and information environments are mostly benign processes with an adversary mixed in, and the adversary adapts to whatever the defender measures. My work follows that problem from end to end: model the contaminated process, establish what can be detected from it with honest confidence, turn that evidence into a defender's action, and ask whether the agents carrying out that action can themselves be trusted.</p>
    <div class="jm-pillars">
      <div class="jm-pillar i">
        <span class="num">I · Identify</span>
        <h3>What does the contaminated process look like?</h3>
        <p>Generative and structural models of normal and adversarial behavior: role-indexed Markov models of ATT&amp;CK tactic transitions on hosts, graphon models of adversarial networks compared under Gromov–Wasserstein distance, and the dynamics of how narratives emerge and drift.</p>
        <div class="jm-tags"><a href="#projects">DRIFT</a><a href="https://jscholarship.library.jhu.edu/items/fd7d6024-7bb5-4360-a7c8-33664ba25914">M.S. thesis</a><a href="https://arxiv.org/abs/2603.17617">Narrative monitoring</a></div>
      </div>
      <div class="jm-pillar d">
        <span class="num">II · Detect</span>
        <h3>What can the defender know?</h3>
        <p>Detectors that report calibrated, verifiable evidence rather than bare alerts: peer-baselined, bootstrap-calibrated divergence scoring with multi-channel corroboration, periodicity and changepoint tests for command-and-control, and uncertainty quantification for model and LLM outputs.</p>
        <div class="jm-tags"><a href="#projects">STRATA-E</a><a href="#projects">CADENCE</a><a href="https://link.springer.com/chapter/10.1007/978-3-032-40581-4_7">SBP-BRiMS '26</a></div>
      </div>
      <div class="jm-pillar x">
        <span class="num">III · Decide</span>
        <h3>What should the defender do?</h3>
        <p>Decision-theoretic use of uncertain evidence: recommending follow-on collection over adversarial networks, and modeling intrusion progression with attack graphs and POMDPs so a defender can choose which analytic or response to run next under a limited budget.</p>
        <div class="jm-tags"><a href="https://jscholarship.library.jhu.edu/items/fd7d6024-7bb5-4360-a7c8-33664ba25914">M.S. thesis</a><span>Current direction</span></div>
      </div>
      <div class="jm-pillar g">
        <span class="num">IV · Delegate</span>
        <h3>Who carries out the decision, and can they be trusted?</h3>
        <p>As hunting shifts to AI agents, the defender's own pipeline becomes a source of contamination: agents err, follow the wrong principal, or exceed their authority. This arc applies the first three to the agent itself. It identifies correct behavior under codified authorities, measures how rarely agents fail, and decides when and to whom to delegate.</p>
        <div class="jm-tags"><span>Current direction</span></div>
      </div>
    </div>
  </section>

  <section id="publications">
    <h2>Publications</h2>
    <ul class="jm-pubs">
      <li>
        <span class="t">Characterizing Behavioral Deviation in Endpoint Telemetry via ATT&amp;CK Transitions</span>
        <span class="a"><b>J. Moody</b>, I. Cruickshank, L. H. X. Ng</span>
        <span class="v">Social, Cultural, and Behavioral Modeling: 19th International Conference, SBP-BRiMS 2026 (Springer LNCS)</span><span class="l"><a href="https://link.springer.com/chapter/10.1007/978-3-032-40581-4_7">[paper]</a> <a href="https://github.com/jackdmoody/DRIFT">[code]</a></span>
      </li>
      <li>
        <span class="t">Temporal Narrative Monitoring in Dynamic Information Environments</span>
        <span class="a">D. Farr, S. Prochaska, <b>J. Moody</b>, L. H. X. Ng, I. Cruickshank, K. Starbird, J. West</span>
        <span class="v">arXiv preprint arXiv:2603.17617, 2026</span><span class="l"><a href="https://arxiv.org/abs/2603.17617">[arXiv]</a></span>
      </li>
      <li>
        <span class="t">Unraveling the Threat: Interpreting Terrorist Groups via Network Analysis and Decision Theory</span>
        <span class="a"><b>J. Moody</b>; advised by T. Woolf</span>
        <span class="v">M.S. thesis, Johns Hopkins University, 2023</span><span class="l"><a href="https://jscholarship.library.jhu.edu/items/fd7d6024-7bb5-4360-a7c8-33664ba25914">[thesis]</a></span>
      </li>
      <li>
        <span class="t">Nuclear Test Film Analysis</span>
        <span class="a"><b>J. Moody</b>; advised by R. Miskimen</span>
        <span class="v">B.S. honors thesis, University of Massachusetts Amherst, 2021</span>
      </li>
    </ul>
  </section>

  <section id="projects">
    <h2>Projects</h2>

    <div class="jm-proj attack">
      <h3>STRATA-E</h3>
      <div class="who">Sole developer · with Cruickshank &amp; Ng</div>
      <p>Structural and Temporal Role-Aware Threat Analytics for Endpoint telemetry. A hierarchical, statistically calibrated anomaly-detection framework for Windows Sysmon and Event logs. Each host is represented as a distribution over MITRE ATT&amp;CK tactic transitions and scored against hierarchical Dirichlet peer-role baselines with bootstrap-calibrated Jensen–Shannon divergence; four corroborating channels (sequence, frequency, context, drift) are fused into a ranked, explainable triage list.</p>
      <div class="links"><a href="https://github.com/jackdmoody/STRATA-E_2">Code</a><span class="dot">•</span>Poster at the MORS AI Workshop</div>
    </div>

    <div class="jm-proj attack">
      <h3>DRIFT</h3>
      <div class="who">Deviation in Role-Indexed ATT&amp;CK Flow Transitions</div>
      <p>Code and experiments for characterizing behavioral deviation in endpoint telemetry through ATT&amp;CK tactic transitions, the basis of the SBP-BRiMS 2026 paper.</p>
      <div class="links"><a href="https://link.springer.com/chapter/10.1007/978-3-032-40581-4_7">Paper</a><span class="dot">•</span><a href="https://github.com/jackdmoody/DRIFT">Code</a></div>
    </div>

    <div class="jm-proj attack">
      <h3>CADENCE</h3>
      <div class="who">C2 Anomaly Detection via Ensemble Network Correlation Evidence</div>
      <p>A multi-stage pipeline for detecting command-and-control beaconing in Zeek telemetry: Isolation Forest screening, autocorrelation and spectral periodicity tests, changepoint detection, and DNS/HTTP/TLS corroboration, with ATT&amp;CK annotation of each finding.</p>
      <div class="links"><a href="https://github.com/jackdmoody/CADENCE">Code</a></div>
    </div>

    <div class="jm-proj narr">
      <h3>Temporal Narrative Monitoring</h3>
      <div class="who">with Farr, Prochaska, Ng, Cruickshank, Starbird &amp; West</div>
      <p>Tracking how narratives emerge, drift, and persist in dynamic information environments, using density-based clustering over sentence embeddings validated on real crisis discourse.</p>
      <div class="links"><a href="https://arxiv.org/abs/2603.17617">Paper</a></div>
    </div>

    <div class="jm-proj">
      <h3>Graphons &amp; Gromov–Wasserstein for Adversarial Networks</h3>
      <div class="who">M.S. thesis · Johns Hopkins</div>
      <p>Generated synthetic adversarial networks from graphons, compared them under the Gromov–Wasserstein distance, clustered the resulting metric-measure spaces, and analyzed the clusters in a decision-theoretic framework to inform courses of action against terrorist networks.</p>
      <div class="links"><a href="https://jscholarship.library.jhu.edu/items/fd7d6024-7bb5-4360-a7c8-33664ba25914">Thesis</a></div>
    </div>
  </section>

  <section id="news">
    <h2>News</h2>
    <ul class="jm-news">
      <li><span class="y">2026</span><span>Presented <a href="https://link.springer.com/chapter/10.1007/978-3-032-40581-4_7"><em>Characterizing Behavioral Deviation in Endpoint Telemetry via ATT&amp;CK Transitions</em></a> at SBP-BRiMS 2026, Carnegie Mellon University.</span></li>
      <li><span class="y">2026</span><span>Preprint: <a href="https://arxiv.org/abs/2603.17617">Temporal Narrative Monitoring in Dynamic Information Environments</a>.</span></li>
      <li><span class="y">2026</span><span>Presented a STRATA-E poster at the Military Operations Research Society (MORS) AI Workshop.</span></li>
      <li><span class="y">2026</span><span>Began an M.S. in Computer Science at CU Boulder.</span></li>
      <li><span class="y">2024</span><span>Received the Order of the Sphinx Award for contributions to intelligence work in the cyber domain.</span></li>
    </ul>
  </section>

  <div class="jm-end">Views are my own and do not reflect the official position of the U.S. Army or DoD.</div>

</div>

<script>
(function(){
  var c=document.getElementById('jm-shield'); if(!c||!c.getContext) return;
  var dpr=window.devicePixelRatio||1, W=96, H=110, S=96/130;
  c.width=W*dpr; c.height=H*dpr; c.style.width=W+'px'; c.style.height=H+'px';
  var g=c.getContext('2d'); g.scale(dpr*S,dpr*S); W=130; H=150;
  var R=[[200,0],[220,10],[240,20],[260,28],[280,36],[300,43],[320,48],[340,53],[360,57],[380,60],[389,66],[393,100],[398,140],[399,180],[396,220],[388,260],[374,300],[352,340],[318,380],[268,420],[233,440],[200,455]];
  var pts=R.map(function(p){return [3+p[0]*0.31, 4+p[1]*0.31];});
  for(var i=R.length-2;i>0;i--){ pts.push([3+(400-R[i][0])*0.31, 4+R[i][1]*0.31]); }
  var cx=0,cy=0; pts.forEach(function(p){cx+=p[0];cy+=p[1];}); cx/=pts.length; cy/=pts.length;
  var edges=[]; for(var k=0;k<pts.length;k++){
    var a=pts[k], b=pts[(k+1)%pts.length], dx=b[0]-a[0], dy=b[1]-a[1], L=Math.hypot(dx,dy);
    var nx=-dy/L, ny=dx/L; if((cx-a[0])*nx+(cy-a[1])*ny<0){nx=-nx;ny=-ny;}
    edges.push({a:a,b:b,nx:nx,ny:ny});
  }
  var ball={x:65,y:45,vx:1.6,vy:0,r:9}, G=0.28, E=0.82, F=0.995, running=false;
  function draw(){
    g.clearRect(0,0,W,H);
    g.beginPath(); g.moveTo(pts[0][0],pts[0][1]);
    for(var i=1;i<pts.length;i++) g.lineTo(pts[i][0],pts[i][1]);
    g.closePath(); g.fillStyle='#e4e6e8'; g.fill();
    g.lineWidth=2; g.strokeStyle='#8fb8e0'; g.stroke();
    g.beginPath(); g.arc(ball.x,ball.y,ball.r,0,Math.PI*2); g.fillStyle='#f0a63a'; g.fill();
  }
  function step(){
    ball.vy+=G; ball.vx*=F; ball.vy*=F; ball.x+=ball.vx; ball.y+=ball.vy;
    edges.forEach(function(e){
      var dx=e.b[0]-e.a[0], dy=e.b[1]-e.a[1], L2=dx*dx+dy*dy;
      var t=Math.max(0,Math.min(1,((ball.x-e.a[0])*dx+(ball.y-e.a[1])*dy)/L2));
      var px=e.a[0]+t*dx, py=e.a[1]+t*dy;
      var d=(ball.x-px)*e.nx+(ball.y-py)*e.ny;
      if(d<ball.r){
        ball.x+=(ball.r-d)*e.nx; ball.y+=(ball.r-d)*e.ny;
        var vn=ball.vx*e.nx+ball.vy*e.ny;
        if(vn<0){ ball.vx-=(1+E)*vn*e.nx; ball.vy-=(1+E)*vn*e.ny; }
      }
    });
    draw();
    var speed=Math.abs(ball.vx)+Math.abs(ball.vy);
    if(speed<0.05 && ball.y>110){ running=false; return; }
    requestAnimationFrame(step);
  }
  function go(){ if(!running){ running=true; requestAnimationFrame(step);} }
  c.addEventListener('click',function(ev){
    var r=c.getBoundingClientRect(), mx=(ev.clientX-r.left)/S, my=(ev.clientY-r.top)/S;
    var ax=ball.x-mx, ay=ball.y-my, L=Math.hypot(ax,ay)||1;
    ball.vx+=ax/L*6+(Math.random()-.5)*2; ball.vy+=-7+ay/L*2;
    go();
  });
  draw(); go();
})();
</script>

<script>
(function(){
  var links=[].slice.call(document.querySelectorAll('.jm-pills a[href^="#"]'));
  function upd(){
    var cur=links[0];
    links.forEach(function(l){ var el=document.querySelector(l.getAttribute('href')); if(el && el.getBoundingClientRect().top<140) cur=l; });
    links.forEach(function(l){ l.classList.toggle('on', l===cur); });
  }
  window.addEventListener('scroll',upd,{passive:true}); upd();
})();
</script>
