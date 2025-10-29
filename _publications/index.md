---
layout: archive
title: "Research"   
permalink: /Research/   
author_profile: true
---

<style>
/* --- Collapsible “theme” blocks --- */
.theme { margin: 1.25rem 0; border: 1px solid #e6e6e6; border-radius: 10px; background: #fff; }
.theme > summary {
  /* clickable header row */
  cursor: pointer; list-style: none; padding: 12px 14px; font-weight: 600;
  display: flex; align-items: center; gap: 10px;
}
.theme > summary::-webkit-details-marker { display: none; } /* hide default marker */
.theme .chev { transition: transform .2s ease; }
.theme[open] .chev { transform: rotate(90deg); }

/* --- One left-image / right-text row (your “table”) --- */
.rcard {
  display: flex; gap: 16px; padding: 14px; border-top: 1px solid #f0f0f0;
}
.rcard:first-of-type { border-top: 1px solid #eee; }

/* image column */
.rcard .img img {
  width: 180px; max-width: 35vw; height: auto;
  border: 1px solid #e6e6e6; border-radius: 8px;
}

/* text column */
.rcard .txt { flex: 1; line-height: 1.55; font-size: 16px; }
.rcard .txt h4 { margin: 0 0 6px 0; font-size: 18px; }

/* link buttons (uses Minimal Mistakes button classes if present) */
.rcard .links a { margin-right: 10px; }

/* mobile */
@media (max-width: 720px) {
  .rcard { flex-direction: column; }
  .rcard .img img { width: 100%; max-width: 100%; }
}
/* Dark mode support */
body[data-theme="dark"] .theme {
  background: #2d2d2d; /* dark card */
  border-color: #444;
}

body[data-theme="dark"] .rcard {
  border-color: #555;
}

body[data-theme="dark"] .rcard .txt {
  color: #ddd; /* make text brighter */
}

body[data-theme="dark"] .rcard .img img {
  border-color: #555;
}

body[data-theme="dark"] .theme > summary {
  color: #eee;
}

body[data-theme="dark"] .chev {
  filter: invert(90%); /* make arrow visible */
}

</style>

Below is an introduction of my research by topics. You can find my published papers and preprints on my [Google Scholar](https://scholar.google.com/citations?user=UCWX53IAAAAJ&hl=en&inst=5778974199078678248) page or a broader list of research projects in my [CV](https://yuanzeliu.github.io/files/LIU%20Yuanze_CV_20251027.pdf).

“Man is born free, but everywhere he is in chains.” Rousseau's famous quote encapsulates my core research interest: understanding the dilemma between our inherent sociality and individuality. Humans, as social animals, are profoundly shaped by society, where we develop our defining traits like language and theory of mind. Yet, unlike eusocial species such as ants or bees, whose social roles are biologically fixed, humans are born with equal potential and eager to exert their autonomy. This ever-lasting tension gives rise to deep questions at intrapersonal, interpersonal, and societal levels. The complexity of these questions fuels my long-term passion for research. 


<!-- ===== Theme 1 ===== -->
<details class="theme">
  <summary><span class="chev">▶</span> Societal Level</summary>

  <div class="rcard">
    <div class="img">
      <img src="/images/Research_LLMAgents.png" alt="Complex contagion schematic">
    </div>
    <div class="txt">
      <h4>Fact-sensitive AI agents in mixed human–AI networks</h4>
      <p>
        We test how fact-sensitive AI agents shape belief updating and <em>de-polarization</em>
        via complex contagion in hybrid networks. The design mirrors field-like exposure patterns
        and measures cascade thresholds, local reinforcement, and global diffusion.
      </p>
      <p class="links">
        <a class="btn btn--primary btn--sm" href="/files/LLMAgentProposal.pdf">PDF</a>
      </p>
    </div>
  </div>

  <!-- Optionally add more rows in the same theme -->
  <div class="rcard">
    <div class="img">
      <img src="/images/research/tradition_network.png" alt="Norm change visualization">
    </div>
    <div class="txt">
      <h4>Cultural practices and norm transitions</h4>
      <p>
        Different practice types create distinct reinforcement structures. We analyze which
        structures sustain pluralism vs. lock-in, and how AI companions can steer toward
        pro-social equilibria with minimal interventions.
      </p>
      <p class="links">
        <a class="btn btn--light btn--sm" href="/files/extended_abstract.pdf">Extended abstract</a>
      </p>
    </div>
  </div>
</details>

<!-- ===== Theme 2 ===== -->
<details class="theme">
  <summary><span class="chev">▶</span> Interpersonal Level</summary>

  <div class="rcard">
    <div class="img">
      <img src="/images/research/broker_agent.png" alt="AI broker agent diagram">
    </div>
    <div class="txt">
      <h4>AI brokers as social facilitators</h4>
      <p>
        We build an online platform where an AI broker schedules, prompts, and summarizes
        cross-group dialogues, measuring trust growth, opinion movement, and retention.
      </p>
      <p class="links">
        <a class="btn btn--light btn--sm" href="/files/protocol.pdf">Protocol</a>
        <a class="btn btn--light btn--sm" href="/files/pre_registration.pdf">Pre-registration</a>
      </p>
    </div>
  </div>
</details>

<!-- ===== Theme 3 ===== -->
<details class="theme">
  <summary><span class="chev">▶</span> Individual Level — Trait Language & Cognitive Ecology</summary>

  <div class="rcard">
    <div class="img">
      <img src="/images/research/fact_model.png" alt="FACT model">
    </div>
    <div class="txt">
      <h4>FACT model of trait language</h4>
      <p>
        We propose a four-factor structure (Fitness, Agency, Communion, Traditionalism) and
        show how ecological demands shape trait semantics in both human judgments and LLM personas.
      </p>
      <p class="links">
        <a class="btn btn--primary btn--sm" href="/files/trait_paper.pdf">PDF</a>
        <a class="btn btn--light btn--sm" href="https://osf.io/xxxx">Data</a>
      </p>
    </div>
  </div>
</details>
