---
layout: page
title: "Tiny Autoregressive Recursive Models"
permalink: /papers/11tinyautoregressive/
---

<div class="paper-page">
  <p class="paper-meta"><strong>Authors:</strong> Paulius Rauba, <strong>Claudio Fanconi</strong>, Mihaela van der Schaar</p>
  <p class="paper-meta"><strong>Affiliations:</strong> University of Cambridge</p>
  <p class="paper-meta"><strong>Venue:</strong> ICLR 2026 Workshop on Recursive Self-Improvement &amp; ICLR 2026 Latent and Implicit Thinking</p>
  <p class="paper-meta paper-meta-links"><strong>Links:</strong> <a class="paper-link-chip paper-link-chip-link" href="https://arxiv.org/abs/2603.08082">Paper</a> <a class="paper-link-chip paper-link-chip-pdf" href="{{ site.baseurl }}/papers/11tinyautoregressive/paper.pdf">PDF</a> <a class="paper-link-chip paper-link-chip-code" href="https://github.com/pauliusrauba/autoregressive-TRM">Code</a></p>

  <figure class="paper-figure">
    <img src="{{ site.baseurl }}/assets/images/tiny.png" alt="Representative figure for Tiny Autoregressive Recursive Models">
</figure>

  <h3>Abstract</h3>
  <p>Tiny Recursive Models (TRMs) have shown strong performance on ARC-AGI via two-step refinement of an internal reasoning state and predicted output, raising the question of whether similar refinement should help autoregressive modelling. This paper proposes an Autoregressive TRM and evaluates it on small autoregressive tasks under compute-matched conditions. To isolate where gains come from, the authors design a suite of models that progressively transform a standard Transformer into a Tiny Autoregressive Recursive Model while fixing block design, token stream, and next-token objective. Across character-level algorithmic tasks, some two-level refinement baselines perform strongly, but the full Autoregressive TRM does not show reliable gains. The results suggest promise for two-step refinement mechanisms in general while cautioning against the specific autoregressive TRM architecture as a primary research direction.</p>
</div>
