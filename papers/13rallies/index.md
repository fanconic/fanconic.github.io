---
layout: page
title: "1000 Rallies: An Event-Camera Dataset and Real-Time Learned Ball-State Estimation for Robotic Table Tennis"
permalink: /papers/13rallies/
---

<div class="paper-page">
  <p class="paper-meta"><strong>Authors:</strong> Raphaela Kreiser*, Asude Aydin*, Yin Bi, <strong>Claudio Fanconi</strong>, Peter Dürr, Naoya Takahashi</p>
  <p class="paper-meta"><em>* denotes equal authorship.</em></p>
  <p class="paper-meta"><strong>Affiliations:</strong> Sony AI, Zurich</p>
  <p class="paper-meta"><strong>Venue:</strong> arXiv preprint, 2026</p>
  <p class="paper-meta"><strong>Note:</strong> Preprint from research completed during my 2023 Sony AI internship.</p>
  <p class="paper-meta paper-meta-links"><strong>Links:</strong> <a class="paper-link-chip paper-link-chip-link" href="https://arxiv.org/abs/2606.25620">Paper</a> <a class="paper-link-chip paper-link-chip-pdf" href="{{ site.baseurl }}/papers/13rallies/paper.pdf">PDF</a></p>

  <figure class="paper-figure">
    <img src="{{ site.baseurl }}/assets/images/1000rallies.png" alt="Figure overview for 1000 Rallies: event-camera perception for robotic table tennis">
    <figcaption>Figure 1: Event-camera perception pipeline for real-time robotic table tennis ball-state estimation.</figcaption>
  </figure>

  <h3>Abstract</h3>
  <p>Robotic table tennis is a demanding testbed for real-time perception because accurate ball-state estimation must happen at high frequency and low latency. This preprint introduces a large-scale event-camera dataset for table tennis, with over 1000 rallies recorded from players ranging from amateurs to elite-level athletes, synchronized with high-speed frame-based cameras to produce pseudo ground-truth labels for ball position, velocity, and spin. The paper trains a convolutional neural network to estimate ball position and image-plane velocity directly from event streams, then uses those predictions inside a Kalman-filter trajectory pipeline. Incorporating event-based velocity reduces bounce-point prediction error relative to a position-only baseline, and the system is integrated with a robotic arm to enable real-time human-robot table tennis rallies driven by event-based perception.</p>
</div>
