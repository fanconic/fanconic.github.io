---
layout: page
title: "Predicting Depression Risk in Patients With Cancer Using Multimodal Data - Algorithm Development Study"
permalink: /papers/06multimodal/
---

<div class="paper-page">
  <p class="paper-meta"><strong>Authors:</strong> Anne de Hond, Marieke van Buchem, <strong>Claudio Fanconi</strong>, Mohana Roy, Douglas Blayney, Ilse Kant, Ewout Steyerberg, Tina Hernandez-Boussard</p>
  <p class="paper-meta"><strong>Affiliations:</strong> Leiden University Medical Center, Stanford University, ETH Zurich, University Medical Center Utrecht</p>
  <p class="paper-meta"><strong>Venue:</strong> JMIR Medical Informatics, 2024 Jan 18</p>
  <p class="paper-meta paper-meta-links"><strong>Links:</strong> <a class="paper-link-chip paper-link-chip-link" href="https://medinform.jmir.org/2024/1/e51925/">Paper</a> <a class="paper-link-chip paper-link-chip-pdf" href="{{ site.baseurl }}/papers/06multimodal/paper.pdf">PDF</a> <a class="paper-link-chip paper-link-chip-code" href="https://gitlab.com/a.a.h.de_hond/predicting-depression-for-cancer-patients">Code</a></p>

  <figure class="paper-figure">
    <img src="{{ site.baseurl }}/assets/images/multimodal.png" alt="Representative figure for Predicting Depression Risk in Patients With Cancer Using Multimodal Data - Algorithm Development Study">
</figure>

  <h3>Abstract</h3>
  <p><strong>Background:</strong> Patients with cancer starting systemic treatment programmes, such as chemotherapy, often develop depression. A prediction model may assist clinicians and health-care teams with early identification of vulnerable patients.</p>

  <p><strong>Objective:</strong> This study aimed to develop a prediction model for depression risk within the first month of cancer treatment.</p>

  <p><strong>Methods:</strong> We included 16,159 patients diagnosed with cancer who started chemo- or radiotherapy between 2008 and 2021. Machine learning models (for example, LASSO logistic regression) and natural language processing models (BERT) were used to build multimodal prediction models based on electronic health record data and unstructured text (patient messages and clinician notes). Performance was assessed on an independent test set (n=5,387, 33%) using AUROC, calibration curves, and decision-curve analysis.</p>

  <p><strong>Results:</strong> Among 16,159 patients, 437 (2.7%) received a depression diagnosis within the first month of treatment. LASSO models based on structured data (AUROC 0.74, 95% CI 0.71-0.78) and structured data plus message classification scores (AUROC 0.74, 95% CI 0.71-0.78) had the strongest discrimination. BERT models were around 0.71 AUROC. The message-only logistic model performed poorly (AUROC 0.54, 95% CI 0.52-0.56), and the clinician-note-only model performed worst (AUROC 0.50, 95% CI 0.49-0.52). Calibration was good for logistic models, while BERT models produced overly extreme risk estimates even after recalibration. Risks were underestimated for female and Black patients.</p>

  <p><strong>Conclusions:</strong> The findings highlight both the promise and limitations of multimodal machine learning for depression-risk prediction in oncology. Further work is needed to validate models externally, refine outcomes and predictors, and address subgroup bias.</p>
</div>
