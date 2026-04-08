---
layout: page
title: "Few-shot Steerable Alignment: Adapting Rewards and LLM Policies with Neural Processes"
permalink: /papers/09preferences/
---

<div class="paper-page">
  <p class="paper-meta"><strong>Authors:</strong> Katarzyna Kobalczyk*, <strong>Claudio Fanconi*</strong>, Hao Sun, Mihaela van der Schaar</p>
  <p class="paper-meta"><em>* denotes equal authorship.</em></p>
  <p class="paper-meta"><strong>Affiliations:</strong> University of Cambridge</p>
  <p class="paper-meta"><strong>Venue:</strong> ICML 2025 Workshop on Models of Human Feedback for AI Alignment (Oral)</p>
  <p class="paper-meta paper-meta-links"><strong>Links:</strong> <a class="paper-link-chip paper-link-chip-link" href="https://arxiv.org/abs/2412.13998">Paper</a> <a class="paper-link-chip paper-link-chip-pdf" href="{{ site.baseurl }}/papers/09preferences/paper.pdf">PDF</a> <a class="paper-link-chip paper-link-chip-code" href="https://github.com/fanconic/few-shot-steerable-alignment">Code</a></p>

  <figure class="paper-figure">
    <img src="{{ site.baseurl }}/assets/images/reward_benchmark.png" alt="Representative figure for Few-shot Steerable Alignment: Adapting Rewards and LLM Policies with Neural Processes">
</figure>

  <h3>Abstract</h3>
  <p>As large language models (LLMs) become increasingly embedded in everyday applications, ensuring alignment with diverse individual preferences is a key challenge. Most current methods assume homogeneous objectives and rely on single-objective fine-tuning, which can miss heterogeneous and partially unobservable user preferences. This paper proposes a framework for few-shot steerable alignment, where latent user preferences are inferred from a small sample of their choices. The method extends the Bradley-Terry-Luce model to heterogeneous preferences with unobserved variability and introduces a practical implementation for reward modelling and LLM fine-tuning via functional parameter-space conditioning. This enables adaptation to individual preferences at inference time and supports outputs across a continuum of behavioural modes. Experiments show data-efficient alignment with diverse human preferences.</p>
</div>
