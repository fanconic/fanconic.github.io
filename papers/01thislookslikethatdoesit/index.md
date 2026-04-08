---
layout: page
title: "This Looks Like That... Does it? Shortcomings of Latent Space Prototype Interpretability in Deep Networks"
permalink: /papers/01thislookslikethatdoesit/
---

<div class="paper-page">
  <p class="paper-meta"><strong>Authors:</strong> Adrian Hoffmann*, <strong>Claudio Fanconi*</strong>, Rahul Rade*, Jonas Kohler</p>
  <p class="paper-meta"><em>* denotes equal authorship.</em></p>
  <p class="paper-meta"><strong>Affiliations:</strong> Department of Computer Science and D-ITET, ETH Zurich</p>
  <p class="paper-meta"><strong>Venue:</strong> ICML 2021 Workshop on Theoretic Foundation, Criticism, and Application Trend of Explainable AI</p>
  <p class="paper-meta paper-meta-links"><strong>Links:</strong> <a class="paper-link-chip paper-link-chip-link" href="https://arxiv.org/abs/2105.02968">Paper</a> <a class="paper-link-chip paper-link-chip-pdf" href="{{ site.baseurl }}/papers/01thislookslikethatdoesit/paper.pdf">PDF</a> <a class="paper-link-chip paper-link-chip-code" href="https://github.com/fanconic/this-does-not-look-like-that">Code</a></p>

  <figure class="paper-figure">
    <img src="{{ site.baseurl }}/assets/images/thislookslikethatdoesit.png" alt="Representative figure for This Looks Like That... Does it? Shortcomings of Latent Space Prototype Interpretability in Deep Networks">
</figure>

  <h3>Abstract</h3>
  <p>Deep neural networks that yield human interpretable decisions by architectural design have become an increasingly popular alternative to post hoc interpretation of traditional black-box models. Among these networks, the arguably most widespread approach is so-called prototype learning, where similarities to learned latent prototypes serve as the basis of classifying unseen data. In this work, we point to a crucial shortcoming of such approaches. Namely, there is a semantic gap between similarity in latent space and input space, which can corrupt interpretability. We design two experiments that exemplify this issue on the socalled ProtoPNet. We find that its interpretability mechanism can be led astray by crafted noise or JPEG compression artefacts, which can lead to incoherent decisions. We argue that practitioners ought to have this shortcoming in mind when deploying prototype-based models in practice.</p>
</div>
