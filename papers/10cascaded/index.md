---
layout: page
title: "Cascaded Language Models for Cost-effective Human-AI Decision-Making"
permalink: /papers/10cascaded/
---

<div class="paper-page">
  <p class="paper-meta"><strong>Authors:</strong> <strong>Claudio Fanconi</strong>, Mihaela van der Schaar</p>
  <p class="paper-meta"><strong>Affiliations:</strong> University of Cambridge</p>
  <p class="paper-meta"><strong>Venue:</strong> NeurIPS 2025 (Poster) &amp; ICML 2025 Workshop on Multi Agent Systems</p>
  <p class="paper-meta paper-meta-links"><strong>Links:</strong> <a class="paper-link-chip paper-link-chip-link" href="https://arxiv.org/abs/2506.11887">Paper</a> <a class="paper-link-chip paper-link-chip-pdf" href="{{ site.baseurl }}/papers/10cascaded/paper.pdf">PDF</a> <a class="paper-link-chip paper-link-chip-code" href="https://github.com/fanconic/cascaded-llms">Code</a></p>

  <figure class="paper-figure">
    <img src="{{ site.baseurl }}/assets/images/cascaded.png" alt="Representative figure for Cascaded Language Models for Cost-effective Human-AI Decision-Making">
</figure>

  <h3>Abstract</h3>
  <p>A challenge in human-AI decision-making is balancing prediction correctness, knowledge and reasoning costs, and confidence in whether to abstain or escalate to human experts. This paper presents a cascaded LLM framework that adaptively delegates tasks across three tiers: a base model, a stronger but costlier model, and a human expert when the model cascade abstains. The method uses a two-stage policy: first, a deferral policy decides whether to accept the base model&#39;s answer or regenerate with the larger model; second, an abstention policy decides whether the cascade output is certain enough or should be referred to a human. An online learning mechanism incorporates human feedback to adapt to changing task difficulty. Evaluations on ARC-Easy, ARC-Challenge, MMLU, MedQA, and MedMCQA show that the cascaded strategy improves accuracy in most settings while reducing cost and handling abstentions in a principled way.</p>
</div>
