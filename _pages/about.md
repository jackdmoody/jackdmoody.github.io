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

<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=IBM+Plex+Mono:wght@400;500&family=IBM+Plex+Sans:wght@400;500;600&family=Spectral:ital,wght@0,300;0,400;0,500;0,600;1,400&display=swap">

<style>
.jm-home{
  --ink:#15212E; --soft:#54677A; --line:#DDE3E9;
  --attack:#A23B3E; --epi:#2E5E8C; --narr:#3C7A69;
  --accent:#2E5E8C; --accent-dk:#21476B;
  --serif:'Spectral',Georgia,serif;
  --sans:'IBM Plex Sans',system-ui,-apple-system,sans-serif;
  --mono:'IBM Plex Mono',ui-monospace,Menlo,monospace;
  max-width:62rem; margin:0 auto; color:var(--ink);
  font-family:var(--sans); line-height:1.55;
}
.jm-home h1,.jm-home h2,.jm-home h3{
  border:0; margin:0; padding:0; color:var(--ink); font-weight:500;
}
.jm-home a{ color:var(--accent); text-decoration:none; }
.jm-home a:hover{ color:var(--accent-dk); text-decoration:underline; }
.jm-home a:focus-visible{ outline:2px solid var(--accent); outline-offset:3px; }

.jm-eyebrow{
  font-family:var(--mono); font-size:.72rem; letter-spacing:.16em;
  text-transform:uppercase; color:var(--soft);
}

/* ---- hero ---- */
.jm-hero{ padding:.5rem 0 0; }
.jm-hero h1{
  font-family:var(--serif); font-weight:500;
  font-size:clamp(1.95rem,4.4vw,2.95rem); line-height:1.16;
  margin:.9rem 0 0; max-width:32ch;
}
.jm-hero h1 em{ font-style:italic; color:var(--accent); }
.jm-lede{
  font-size:1.05rem; color:var(--soft); max-width:42rem; margin:1.1rem 0 0;
}
.jm-links{
  font-family:var(--mono); font-size:.82rem; margin:1.4rem 0 0;
  display:flex; flex-wrap:wrap; gap:.35rem 1.1rem;
}

/* three-layer signature divider */
.jm-triad{
  height:3px; border:0; margin:2.6rem 0;
  background:linear-gradient(90deg,
    var(--attack) 0 33.33%, var(--epi) 33.33% 66.66%, var(--narr) 66.66% 100%);
}

/* ---- agenda ---- */
.jm-sechead h2{
  font-family:var(--serif); font-size:clamp(1.45rem,3vw,2rem); margin:.5rem 0 0;
}
.jm-sechead p{ color:var(--soft); margin:.5rem 0 0; max-width:42rem; }

.jm-grid{
  display:grid; grid-template-columns:repeat(3,1fr);
  gap:1rem; margin:1.6rem 0 0;
}
.jm-card{
  border:1px solid var(--line); border-left:3px solid var(--c,var(--accent));
  border-radius:2px; padding:1.1rem 1.1rem 1.2rem; background:#fff;
  transition:transform .18s ease, box-shadow .18s ease;
}
.jm-card:hover{ transform:translateY(-2px); box-shadow:0 8px 24px rgba(21,33,46,.08); }
.jm-card .jm-eyebrow{ color:var(--c,var(--accent)); }
.jm-card h3{ font-family:var(--sans); font-weight:600; font-size:1.05rem; margin:.5rem 0 0; }
.jm-card p{ font-size:.92rem; color:var(--soft); margin:.55rem 0 0; }
.jm-tag{
  display:inline-block; font-family:var(--mono); font-size:.7rem;
  letter-spacing:.04em; margin-top:.8rem; padding:.15rem .5rem;
  border:1px solid var(--line); border-radius:2px; color:var(--ink);
}
.jm-a1{ --c:var(--attack); } .jm-a2{ --c:var(--epi); } .jm-a3{ --c:var(--narr); }

/* ---- featured (the one bold block) ---- */
.jm-feature{
  margin:2.6rem 0 0; background:var(--ink); color:#EAF0F6;
  border-radius:3px; padding:1.7rem 1.6rem;
}
.jm-feature .jm-eyebrow{ color:#9BB4CC; }
.jm-feature h3{
  font-family:var(--serif); color:#fff; font-weight:500;
  font-size:1.7rem; letter-spacing:.01em; margin:.5rem 0 0;
}
.jm-feature p{ color:#C7D4E0; margin:.8rem 0 0; max-width:46rem; }
.jm-feature .jm-meta{ font-family:var(--mono); font-size:.74rem; color:#8FA6BC; margin:1rem 0 0; }
.jm-feature a{ color:#9FD0FF; }
.jm-feature a:hover{ color:#CDE6FF; }
.jm-btns{ margin:1.2rem 0 0; display:flex; flex-wrap:wrap; gap:.6rem; }
.jm-btn{
  font-family:var(--mono); font-size:.78rem; padding:.5rem .9rem;
  border:1px solid #38516B; border-radius:2px; color:#EAF0F6 !important;
}
.jm-btn:hover{ background:#1E3146; text-decoration:none; }

/* ---- news ---- */
.jm-news{ list-style:none; padding:0; margin:1.4rem 0 0; }
.jm-news li{
  display:flex; gap:1rem; padding:.6rem 0; border-bottom:1px solid var(--line);
  font-size:.95rem;
}
.jm-news .jm-date{
  font-family:var(--mono); font-size:.78rem; color:var(--soft);
  flex:0 0 4.5rem; padding-top:.1rem;
}

/* ---- about ---- */
.jm-about p{ color:var(--ink); max-width:46rem; margin:1rem 0 0; }
.jm-contact{ font-family:var(--mono); font-size:.82rem; margin:1.2rem 0 0;
  display:flex; flex-wrap:wrap; gap:.35rem 1.1rem; }

.jm-sec{ margin:2.6rem 0 0; }

@media (max-width:680px){
  .jm-grid{ grid-template-columns:1fr; }
}
@media (prefers-reduced-motion:reduce){
  .jm-card{ transition:none; }
  .jm-card:hover{ transform:none; }
}
</style>

<div class="jm-home" markdown="0">

  <section class="jm-hero">
    <span class="jm-eyebrow">U.S. Army Cyber Warfare Officer · Applied Mathematician</span>
    <h1>Adversaries and crowds both leave noisy, shifting traces. I build models that turn them into <em>calibrated, verifiable evidence</em> — signals a decision-maker can trust.</h1>
    <p class="jm-lede">I work across adversarial machine learning, statistical network science, and uncertainty quantification — applied to cyber telemetry and online influence operations, where a confident wrong answer is expensive.</p>
    <nav class="jm-links">
      <a href="#research">Research</a>
      <a href="/publications/">Publications</a>
      <a href="/cv/">CV</a>
      <a href="https://scholar.google.com/">Google&nbsp;Scholar</a>
      <a href="https://github.com/jackdmoody">GitHub</a>
    </nav>
  </section>

  <hr class="jm-triad">

  <section id="research" class="jm-sechead">
    <span class="jm-eyebrow">Research Agenda</span>
    <h2>Three layers, one problem.</h2>
    <p>A single program for reasoning about adversarial and social systems under uncertainty — detect the behavior, establish that it's real and attributable, then situate it in context.</p>

    <div class="jm-grid">
      <article class="jm-card jm-a1">
        <span class="jm-eyebrow">Attack Layer</span>
        <h3>Adversarial ML &amp; decision-theoretic defense</h3>
        <p>Behavioral anomaly detection over ICS/SCADA and endpoint telemetry; Bayesian attack graphs and POMDPs for modeling how an intrusion actually progresses.</p>
        <span class="jm-tag">STRATA-E</span>
      </article>
      <article class="jm-card jm-a2">
        <span class="jm-eyebrow">Epistemic Layer</span>
        <h3>Calibration &amp; evidence-grounded attribution</h3>
        <p>Making model outputs verifiable — uncertainty quantification, LLM calibration, and conformal methods so a claim arrives with an honest confidence and a trail of evidence.</p>
        <span class="jm-tag">Verifiability</span>
      </article>
      <article class="jm-card jm-a3">
        <span class="jm-eyebrow">Narrative Layer</span>
        <h3>Influence operations &amp; network science</h3>
        <p>Tracking how narratives emerge, drift, and persist in dynamic information environments — density-based clustering over sentence embeddings, validated on real crisis discourse (with Starbird and West).</p>
        <span class="jm-tag">Narrative monitoring</span>
      </article>
    </div>
  </section>

  <section class="jm-feature">
    <span class="jm-eyebrow">Featured Work</span>
    <h3>STRATA-E</h3>
    <p>Structural and Temporal Role-Aware Threat Analytics for Endpoint telemetry — a hierarchical, statistically calibrated anomaly-detection framework for Windows Sysmon and Event logs. It represents each host as a distribution over MITRE ATT&amp;CK tactic transitions, scores deviation against hierarchical Dirichlet peer-role baselines with bootstrap-calibrated Jensen–Shannon divergence, and fuses four corroborating channels — sequence, frequency, context, and drift — into a ranked, explainable triage list. Evaluated on a 30.5-million-event corpus spanning 27 hosts across five operational roles.</p>
    <div class="jm-btns">
      <a class="jm-btn" href="#">Read the preprint</a>
      <a class="jm-btn" href="https://github.com/jackdmoody/STRATA-E_2">View the code</a>
    </div>
    <p class="jm-meta">Sole developer · preprint with Cruickshank &amp; Ng · presented at the MORS AI Workshop</p>
  </section>

  <section class="jm-sec">
    <span class="jm-eyebrow">Selected News</span>
    <ul class="jm-news">
      <li><span class="jm-date">2026</span><span>Preprint: <em>Characterizing Behavioral Deviation in Endpoint Telemetry via ATT&amp;CK Transitions</em> (the STRATA-E paper), with Cruickshank and Ng.</span></li>
      <li><span class="jm-date">2026</span><span>Preprint: <em>Temporal Narrative Monitoring in Dynamic Information Environments</em> — <a href="https://arxiv.org/abs/2603.17617">arXiv:2603.17617</a>, with Farr, Prochaska, Ng, Cruickshank, Starbird, and West.</span></li>
      <li><span class="jm-date">2026</span><span>Presented STRATA-E at the Military Operations Research Society (MORS) AI Workshop.</span></li>
      <li><span class="jm-date">2026</span><span>Began an M.S. in Computer Science at CU Boulder.</span></li>
      <li><span class="jm-date">2024</span><span>Received the Order of the Sphinx Award for contributions to military intelligence in the cyber domain.</span></li>
    </ul>
  </section>

  <section class="jm-sec jm-about">
    <span class="jm-eyebrow">About</span>
    <p>I'm a U.S. Army Cyber Warfare Officer. I command a 170-person company in the Cyber Protection Brigade and serve as one of five Senior Analytic Support Officers in the Army, leading machine-learning and analytic pipelines that identify malicious cyber activity for national-level defensive missions.</p>
    <p>I hold an M.S. in Applied &amp; Computational Mathematics from Johns Hopkins — a thesis on graphons and Gromov–Wasserstein distance for adversarial network analysis — and a B.S. in Physics from UMass Amherst, and I'm completing an M.S. in Computer Science at CU Boulder. I also teach graduate stochastic differential equations and theory of statistics at Hopkins.</p>
    <nav class="jm-contact">
      <a href="mailto:jackdmoody@pm.me">jackdmoody@pm.me</a>
      <a href="https://scholar.google.com/">Google&nbsp;Scholar</a>
      <a href="https://github.com/jackdmoody">GitHub</a>
      <a href="https://www.linkedin.com/">LinkedIn</a>
    </nav>
  </section>

</div>
