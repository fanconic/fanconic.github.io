---
layout: page
title: "Natural Language Processing Methods to Identify Oncology Patients at High Risk for Acute Care with Clinical Notes"
permalink: /papers/03nlponcology/
---

<div class="paper-page">
  <p class="paper-meta"><strong>Authors:</strong> <strong>Claudio Fanconi</strong>, Marieke van Buchem, Tina Hernandez-Boussard</p>
  <p class="paper-meta"><strong>Affiliations:</strong> Stanford University, ETH Zurich, Leiden University Medical Center</p>
  <p class="paper-meta"><strong>Venue:</strong> AMIA 2023 Informatics Summit (Presentation)</p>
  <p class="paper-meta paper-meta-links"><strong>Links:</strong> <a class="paper-link-chip paper-link-chip-link" href="https://arxiv.org/abs/2209.13860">Paper</a> <a class="paper-link-chip paper-link-chip-pdf" href="{{ site.baseurl }}/papers/03nlponcology/paper.pdf">PDF</a> <a class="paper-link-chip paper-link-chip-code" href="https://github.com/su-boussard-lab/nlp-for-acu">Code</a></p>

  <figure class="paper-figure">
    <img src="{{ site.baseurl }}/assets/images/nlp_onc.png" alt="Representative figure for Natural Language Processing Methods to Identify Oncology Patients at High Risk for Acute Care with Clinical Notes">
</figure>

  <h3>Abstract</h3>
  <p>Clinical notes are an essential component of a health record. This paper evaluates how natural language processing (NLP) can be used to identify the risk of acute care use (ACU) in oncology patients once chemotherapy starts. Risk prediction using structured health data (SHD) is now standard, but predictions using free-text formats are complex. This paper explores the use of free-text notes for predicting ACU in lieu of SHD. Deep learning models were compared to manually engineered language features. Results show that SHD models minimally outperform NLP models: an l1-penalised logistic regression with SHD achieved a C-statistic of 0.748 (95% CI 0.735-0.762), while the same model with language features achieved 0.730 (95% CI 0.717-0.745) and a transformer-based model achieved 0.702 (95% CI 0.688-0.717). This paper shows how language models can be used in clinical applications and underlines how risk bias differs across patient groups, even when using only free-text data.</p>
</div>
