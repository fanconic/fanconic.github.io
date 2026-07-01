---
layout: page
title: "Learning Reasoning Rewards from Expert Demonstrations with Inverse Reinforcement Learning"
permalink: /papers/12adversarial_irl/
---

<div class="paper-page">
  <p class="paper-meta"><strong>Authors:</strong> <strong>Claudio Fanconi</strong>, Nicolas Astorga, Mihaela van der Schaar</p>
  <p class="paper-meta"><strong>Affiliations:</strong> University of Cambridge</p>
  <p class="paper-meta"><strong>Venue:</strong> ICLR 2026 Workshop on LLM Reasoning &amp; ICML 2026 Workshop on Decision-Making from Offline Datasets to Online Adaptation</p>
  <p class="paper-meta paper-meta-links"><strong>Links:</strong> <a class="paper-link-chip paper-link-chip-link" href="https://arxiv.org/abs/2510.01857">Paper</a> <a class="paper-link-chip paper-link-chip-pdf" href="{{ site.baseurl }}/papers/12adversarial_irl/paper.pdf">PDF</a> <a class="paper-link-chip paper-link-chip-code" href="https://github.com/fanconic/expert_reasoning">Code</a></p>

  <figure class="paper-figure">
    <img src="{{ site.baseurl }}/assets/images/inverse.png" alt="Figure 1 overview for Learning Reasoning Rewards from Expert Demonstrations with Inverse Reinforcement Learning">
    <figcaption>Figure 1: R-AIRL learns reasoning rewards from expert demonstrations and reuses the reward for training, reranking, and diagnostics.</figcaption>
  </figure>

  <h3>Abstract</h3>
  <p>Teaching large language models to reason during post-training often relies on reinforcement learning with explicit outcome- or process-based rewards, but such reward functions can be difficult to obtain or define for complex tasks. This paper proposes Reasoning Adversarial Inverse Reinforcement Learning (R-AIRL), which learns process-level reasoning rewards directly from expert chain-of-thought demonstrations instead of imitating expert traces through supervised fine-tuning. The learned reward can be reused across the reasoning pipeline: as a post-training signal, for inference-time reranking, and for process-level diagnostics that localise reasoning failures. Across GSM8K, MMLU-Pro, and MedReason, R-AIRL improves over supervised fine-tuning in most settings, increases pass@1 through reranking by up to 17.4 points, and localises reasoning failures with up to 86.1% accuracy.</p>
</div>
