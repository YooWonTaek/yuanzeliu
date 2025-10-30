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
        <a class="btn btn--primary btn--sm" href="/files/Proposal Pitch- Cultural Evolution in Human-AI Hybrid Networks.docx">Proposal</a>
      </p>
    </div>
  </div>

  <!-- Optionally add more rows in the same theme -->
  <div class="rcard">
  <div class="img">
    <img src="/images/Research_CivilRights.png" alt="Norm change visualization">
  </div>
  <div class="txt">
    <h4>Historical polarization in legislative support for civil rights in the United States</h4>
    <p>
      Sixty years after the civil rights movement, we examine the historical trajectory of civil rights through the language of US legislation. Using natural language processing (NLP), we find that civil rights has become a more common but also a more polarized policy area. Polarization between Democrats and Republicans accelerated during the early 1990s and the mid-2010s. The latter acceleration coincided with the rise of the “Black Lives Matter” movement, and it was driven by a surge of legislative support for civil rights among racial minority Democrats. Content analyses show that civil rights legislation supporting racial minorities, women and the LGBTQ+ community has polarized most, while legislation supporting the elderly and disabled has declined in both parties. Our findings offer new insights into party polarization, race and ethnicity politics, and collective action tipping points. We showcase NLP as a valuable method for studying the changing behavior of political elites.
    </p>
    <p class="citation">
      Jackson, J. C., <strong>Liu, Y.</strong>, & Kteily, N. S. (R&R). 
      Historical polarization in legislative support for civil rights in the United States.
      <em>Nature Communications</em>.
    </p>

    <p class="links">
      <a class="btn btn--light btn--sm" href="https://doi.org/10.31234/osf.io/7cqfs_v3">Preprint</a>
    </p>
  </div>
</div>
<div class="rcard">
  <div class="img">
    <img src="/images/Research_PredjudiceState.png" alt="Prejudice and State Centralization">
  </div>

  <div class="txt">
    <h4>Prejudice tied to state centralization in historical societies</h4>

    <p>
      Prejudice perpetuates social inequalities, shapes policies, and exacerbates conflicts. Despite its prevalence in modern human life, the origins of prejudice remain unclear. Using novel methods of historical text analysis, we test ecological and structural theories of how prejudice evolves. First, we code 389 ethnographic sources from 90 societies, finding that horizontal prejudice (group-based dislike) and vertical prejudice (superiority beliefs) are positively associated with state centralization but not with environmental threat, pathogens, or warfare. Second, we analyze ethnic prejudice in Chinese historical records (206 BCE–1911 CE) using a large language model, similarly showing that prejudice intensified during state centralization and diminished during decentralized governance. These findings challenge the notion of prejudice as universal, suggesting instead that prejudice co-evolves with social structure.
    </p>

    <p class="citation">
      Dillion, D., <strong>Liu, Y.</strong>, Chen Y., Watts, J., Zhao, C., Baral, S., Bucker, W., Atari, M., Kteily, N., & Jackson, J. (under review).
      Prejudice tied to state centralization in historical societies.
      <em>Science Advances</em>.
    </p>

    <p class="links">
      <a class="btn btn--light btn--sm" href="https://doi.org/10.31234/osf.io/zxuth">Preprint</a>
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
