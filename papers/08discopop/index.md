---
layout: page
title: "Discovering Preference Optimization Algorithms with and for Large Language Models"
permalink: /papers/08discopop/
---

<div class="paper-page">
  <p class="paper-meta"><strong>Authors:</strong> Chris Lu*, Samuel Holt*, <strong>Claudio Fanconi*</strong>, Alex J. Chan, Jakob Foerster‡, Mihaela van der Schaar‡, Robert Tjarko Lange‡</p>
  <p class="paper-meta"><em>* denotes equal authorship.</em></p>
  <p class="paper-meta"><strong>Affiliations:</strong> University of Cambridge, University of Oxford, Sakana AI</p>
  <p class="paper-meta"><strong>Venue:</strong> NeurIPS 2024 (Poster) &amp; ICML 2024 Workshop on AutoRL</p>
  <p class="paper-meta paper-meta-links"><strong>Links:</strong> <a class="paper-link-chip paper-link-chip-link" href="https://neurips.cc/virtual/2024/poster/94244">Paper</a> <a class="paper-link-chip paper-link-chip-pdf" href="{{ site.baseurl }}/papers/08discopop/paper.pdf">PDF</a> <a class="paper-link-chip paper-link-chip-code" href="https://github.com/luchris429/Discopop">Code</a></p>

  <figure class="paper-figure">
    <img src="{{ site.baseurl }}/assets/images/discopop.gif" alt="Representative figure for Discovering Preference Optimization Algorithms with and for Large Language Models">
</figure>

  <h3>Abstract</h3>
  <p>Offline preference optimization is a key method for enhancing and controlling the quality of Large Language Model (LLM) outputs. Typically, preference optimization is approached as an offline supervised learning task using manually crafted convex loss functions. While these methods are based on theoretical insights, they are inherently constrained by human creativity, so the large search space of possible loss functions remains under-explored. We address this by performing LLM-driven objective discovery to automatically discover new state-of-the-art preference optimization algorithms without (expert) human intervention. Specifically, we iteratively prompt an LLM to propose and implement new preference optimization loss functions based on previously evaluated performance metrics. This process leads to the discovery of previously unknown and performant preference optimization algorithms. The best performing of these we call Discovered Preference Optimization (DiscoPOP)1 , a novel algorithm that adaptively blends logistic and exponential losses. Experiments demonstrate the state-of-the-art performance of DiscoPOP and its successful transfer to held-out tasks.</p>
</div>
