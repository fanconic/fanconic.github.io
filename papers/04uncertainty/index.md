---
layout: page
title: "A Bayesian Approach to Predictive Uncertainty in Chemotherapy Patients at Risk of Acute Care Use"
permalink: /papers/04uncertainty/
---

<div class="paper-page">
  <p class="paper-meta"><strong>Authors:</strong> <strong>Claudio Fanconi</strong>, Anne de Hond, Dylan Peterson, Angelo Capodici, Tina Hernandez-Boussard</p>
  <p class="paper-meta"><strong>Affiliations:</strong> ETH Zurich, Stanford University, Leiden University Medical Center, University of Bologna</p>
  <p class="paper-meta"><strong>Venue:</strong> The Lancet eBioMedicine, Volume 92, 2023</p>
  <p class="paper-meta paper-meta-links"><strong>Links:</strong> <a class="paper-link-chip paper-link-chip-link" href="https://www.sciencedirect.com/science/article/pii/S2352396423001974">Paper</a> <a class="paper-link-chip paper-link-chip-pdf" href="{{ site.baseurl }}/papers/04uncertainty/paper.pdf">PDF</a> <a class="paper-link-chip paper-link-chip-code" href="https://github.com/su-boussard-lab/acu-uncertainty-estimation">Code</a></p>

  <figure class="paper-figure">
    <img src="{{ site.baseurl }}/assets/images/uncertainty.png" alt="Representative figure for A Bayesian Approach to Predictive Uncertainty in Chemotherapy Patients at Risk of Acute Care Use">
</figure>

  <h3>Abstract</h3>
  <p><strong>Background:</strong> Machine learning (ML) predictions are becoming increasingly integrated into medical practice. One commonly used method, l1-penalised logistic regression (LASSO), can estimate patient risk for disease outcomes but is limited to point estimates. Bayesian logistic LASSO regression (BLLR) models instead provide predictive distributions and uncertainty estimates, but are less commonly implemented.</p>

  <p><strong>Methods:</strong> This study evaluated the predictive performance of multiple BLLR variants against standard logistic LASSO using real-world, high-dimensional, structured electronic health record data from patients with cancer initiating chemotherapy. Models were compared using an 80-20 split and 10-fold cross-validation to predict acute care utilisation (ACU) after treatment start.</p>

  <p><strong>Findings:</strong> The study included 8,439 patients. The LASSO model achieved an AUROC of 0.806 (95% CI 0.775-0.834). BLLR with a Horseshoe+ prior and Metropolis-Hastings posterior approximation achieved similar performance at 0.807 (95% CI 0.780-0.834), while also providing uncertainty estimates for each prediction. BLLR identified cases too uncertain for automatic classification, and predictive uncertainty differed significantly across race, cancer type, and stage.</p>

  <p><strong>Interpretation:</strong> BLLR offers similar predictive performance to standard LASSO while improving explainability via uncertainty-aware risk estimates. It can also identify patient subgroups with higher uncertainty, which can support clinical decision-making.</p>

  <p><strong>Funding:</strong> This work was supported in part by the National Library of Medicine of the National Institutes of Health under Award Number R01LM013362.</p>
</div>
