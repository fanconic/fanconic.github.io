---
layout: page
title: "Learning Reasoning Reward Models from Expert Demonstration via Inverse Reinforcement Learning"
permalink: /papers/12adversarial_irl/
---

<div class="paper-page">
  <p class="paper-meta"><strong>Authors:</strong> <strong>Claudio Fanconi</strong>, Nicolas Astorga, Mihaela van der Schaar</p>
  <p class="paper-meta"><strong>Affiliations:</strong> University of Cambridge</p>
  <p class="paper-meta"><strong>Venue:</strong> ICLR 2026 Workshop on LLM Reasoning</p>
  <p class="paper-meta paper-meta-links"><strong>Links:</strong> <a class="paper-link-chip paper-link-chip-link" href="https://arxiv.org/abs/2510.01857">Paper</a> <a class="paper-link-chip paper-link-chip-pdf" href="{{ site.baseurl }}/papers/12adversarial_irl/paper.pdf">PDF</a> <a class="paper-link-chip paper-link-chip-code" href="https://github.com/fanconic/expert_reasoning">Code</a></p>

  <figure class="paper-figure">
    <img src="{{ site.baseurl }}/assets/images/inverse.png" alt="Representative figure for Learning Reasoning Reward Models from Expert Demonstration via Inverse Reinforcement Learning">
</figure>

  <h3>Abstract</h3>
  <p>Reasoning in large language models is typically trained via supervised fine-tuning on expert traces or reinforcement learning with outcome-based rewards. Supervised imitation does not directly optimise sequential decision quality, while outcome-based RL requires explicit reward design. This paper proposes an inverse reinforcement learning framework that learns partially dense token-level reasoning rewards directly from expert demonstrations. The learned reward is used both as a dense training signal and as an inference-time reranking signal. Compared with supervised baselines, the approach reports gains on GSM8K (79% vs 56%) and MedReason (74% vs 65%), and up to 12 percentage-point improvements through reward-guided reranking on Llama3 architectures. The learned dense rewards also provide interpretable step-wise diagnostics for localising reasoning errors.</p>
</div>
