---
permalink: /publications/
title: ""
author_profile: false
layout: single
---

<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=IBM+Plex+Mono:wght@400;500&family=IBM+Plex+Sans:wght@400;500;600&family=Spectral:ital,wght@0,300;0,400;0,500;0,600;1,400&display=swap">
<style>
.jm-home{ --ink:#15212E; --soft:#54677A; --line:#DDE3E9; --attack:#A23B3E; --epi:#2E5E8C; --narr:#3C7A69; --accent:#2E5E8C; --accent-dk:#21476B; --serif:'Spectral',Georgia,serif; --sans:'IBM Plex Sans',system-ui,-apple-system,sans-serif; --mono:'IBM Plex Mono',ui-monospace,Menlo,monospace; max-width:62rem; margin:0 auto; color:var(--ink); font-family:var(--sans); line-height:1.55; }
.jm-home h1,.jm-home h2,.jm-home h3{ border:0; margin:0; padding:0; color:var(--ink); font-weight:500; }
.jm-home a{ color:var(--accent); text-decoration:none; }
.jm-home a:hover{ color:var(--accent-dk); text-decoration:underline; }
.jm-eyebrow{ font-family:var(--mono); font-size:.72rem; letter-spacing:.16em; text-transform:uppercase; color:var(--soft); }
.jm-triad{ height:3px; border:0; margin:1.6rem 0 2.2rem; background:linear-gradient(90deg, var(--attack) 0 33.33%, var(--epi) 33.33% 66.66%, var(--narr) 66.66% 100%); }
.jm-pagehead h1{ font-family:var(--serif); font-size:clamp(1.9rem,4vw,2.7rem); margin:.7rem 0 0; }
.jm-pagehead p{ color:var(--soft); margin:.7rem 0 0; max-width:44rem; }
.jm-secblock{ margin:2.4rem 0 0; }
.jm-secblock > .jm-eyebrow{ display:block; margin-bottom:1rem; }
.jm-entry{ border-left:3px solid var(--c,var(--line)); padding:.1rem 0 .1rem 1.1rem; margin:0 0 1.6rem; }
.jm-entry h3{ font-family:var(--serif); font-weight:500; font-size:1.2rem; line-height:1.3; }
.jm-authors{ font-size:.9rem; color:var(--soft); margin:.35rem 0 0; }
.jm-authors strong{ color:var(--ink); font-weight:600; }
.jm-venue{ font-family:var(--mono); font-size:.74rem; color:var(--soft); margin:.35rem 0 0; }
.jm-sum{ font-size:.92rem; color:var(--soft); margin:.5rem 0 0; max-width:46rem; }
.jm-elinks{ font-family:var(--mono); font-size:.78rem; margin:.55rem 0 0; display:flex; flex-wrap:wrap; gap:.3rem .9rem; }
.jm-ltag{ display:inline-block; font-family:var(--mono); font-size:.6rem; letter-spacing:.08em; text-transform:uppercase; padding:.14rem .45rem; border-radius:2px; color:#fff; background:var(--c,var(--soft)); vertical-align:.18em; margin-left:.4rem; }
.jm-a1{ --c:var(--attack); } .jm-a2{ --c:var(--epi); } .jm-a3{ --c:var(--narr); }
</style>

<div class="jm-home" markdown="0">
  <div class="jm-pagehead">
    <span class="jm-eyebrow">Publications</span>
    <h1>Papers, preprints &amp; theses.</h1>
    <p>Work across the three layers — adversarial detection, epistemic calibration, and narrative dynamics. Author order as published; my name in bold.</p>
  </div>
  <hr class="jm-triad">

  <div class="jm-secblock">
    <span class="jm-eyebrow">Preprints</span>

    <div class="jm-entry jm-a1">
      <h3>Characterizing Behavioral Deviation in Endpoint Telemetry via ATT&amp;CK Transitions <span class="jm-ltag">Attack</span></h3>
      <p class="jm-authors"><strong>Moody, J.</strong>, Cruickshank, I., &amp; Ng, L.H.X.</p>
      <p class="jm-venue">Preprint · June 2026</p>
      <p class="jm-sum">Represents each endpoint as a probability distribution over MITRE ATT&amp;CK tactic transitions under two complementary encodings, scored against a leave-one-out role-peer baseline to derive three corroborating deviation signals with bootstrap uncertainty quantification. On a 30.5-million-event Sysmon corpus (27 hosts, five operational roles), the rankings agree on 11 of 12 candidate hosts and surface a single host flagged by all three signals.</p>
      <p class="jm-elinks"><a href="#">Preprint</a><a href="https://github.com/jackdmoody/STRATA-E_2">Code</a></p>
    </div>

    <div class="jm-entry jm-a3">
      <h3>Temporal Narrative Monitoring in Dynamic Information Environments <span class="jm-ltag">Narrative</span></h3>
      <p class="jm-authors">Farr, D., Prochaska, S., <strong>Moody, J.</strong>, Ng, L.H.X., Cruickshank, I., Starbird, K., &amp; West, J.</p>
      <p class="jm-venue">Preprint · March 2026 · arXiv:2603.17617 [cs.SI]</p>
      <p class="jm-sum">A systems-oriented framework that models emerging narratives as temporally evolving semantic structures, using density-based clustering and rolling temporal linkage over sentence embeddings to track persistence, drift, and lifecycle without predefined labels. Achieves 91% cluster-assignment coherence under stratified human validation on discourse around a January 2026 crisis event.</p>
      <p class="jm-elinks"><a href="https://arxiv.org/abs/2603.17617">arXiv</a></p>
    </div>
  </div>

  <div class="jm-secblock">
    <span class="jm-eyebrow">Theses</span>

    <div class="jm-entry jm-a3">
      <h3>Unraveling the Threat: Interpreting Terrorist Groups via Network Analysis and Decision Theory <span class="jm-ltag">Narrative</span></h3>
      <p class="jm-authors"><strong>Moody, J.</strong> · M.S. thesis, Johns Hopkins University · advised by Dr. Thomas Woolf</p>
      <p class="jm-venue">Applied &amp; Computational Mathematics · December 2023</p>
      <p class="jm-sum">Generates synthetic adversarial networks via graphons, compares them under the Gromov–Wasserstein distance, clusters the resulting metric-measure spaces with K-means, and analyzes the clusters through a decision-theoretic framework to inform courses of action.</p>
      <p class="jm-elinks"><a href="#">JScholarship</a></p>
    </div>

    <div class="jm-entry">
      <h3>Nuclear Test Film Analysis</h3>
      <p class="jm-authors"><strong>Moody, J.</strong> · B.S. honors thesis, UMass Amherst · advised by Dr. Rory Miskimen</p>
      <p class="jm-venue">Department of Physics · March 2021</p>
      <p class="jm-sum">An image-analysis pipeline (RGB channel separation, Otsu and Yen thresholding, information-entropy smoothing) to extract ejecta trajectories, velocities, and launch angles from digitized nuclear test films.</p>
    </div>
  </div>

  <div class="jm-secblock">
    <span class="jm-eyebrow">Selected Talks</span>

    <div class="jm-entry jm-a1">
      <h3>STRATA-E: Structural and Temporal Role-Aware Threat Analytics for Endpoint Telemetry</h3>
      <p class="jm-venue">Poster · Military Operations Research Society (MORS) AI Workshop · 2026</p>
    </div>

    <div class="jm-entry jm-a3">
      <h3>Unraveling the Threat: Interpreting Terrorist Groups via Network Analysis and Decision Theory</h3>
      <p class="jm-venue">Talk · CPB Cyber Threat Summit (2024) · 780th MI Brigade AvengerCon (2024)</p>
    </div>
  </div>

  <div class="jm-secblock">
    <span class="jm-eyebrow">Public Writing</span>

    <div class="jm-entry">
      <h3>Staying Motivated and Productive During COVID-19 as an Undergraduate Student</h3>
      <p class="jm-venue">APS News, Back Page · American Physical Society · June 2020</p>
    </div>
  </div>
</div>
