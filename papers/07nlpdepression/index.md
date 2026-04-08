---
layout: page
title: "Applying Natural Language Processing to Patient Messages to Identify Depression Concerns in Cancer Patients"
permalink: /papers/07nlpdepression/
---

<div class="paper-page">
  <p class="paper-meta"><strong>Authors:</strong> Marieke van Buchem, Anne de Hond, <strong>Claudio Fanconi</strong>, Vaibhavi Shah, Max Schuessler, Ilse Kant, Ewout W Steyerberg, Tina Hernandez-Boussard</p>
  <p class="paper-meta"><strong>Affiliations:</strong> Stanford University and collaborating clinical research institutions, as listed in the publication</p>
  <p class="paper-meta"><strong>Venue:</strong> Journal of the American Medical Informatics Association</p>
  <p class="paper-meta paper-meta-links"><strong>Links:</strong> <a class="paper-link-chip paper-link-chip-link" href="https://pubmed.ncbi.nlm.nih.gov/39018490/">Paper</a> <a class="paper-link-chip paper-link-chip-pdf" href="{{ site.baseurl }}/papers/07nlpdepression/paper.pdf">PDF</a> <span class="paper-link-chip paper-link-chip-muted">Code not available</span></p>

  <figure class="paper-figure">
    <img src="{{ site.baseurl }}/assets/images/nlpdepression.png" alt="Representative figure for Applying Natural Language Processing to Patient Messages to Identify Depression Concerns in Cancer Patients">
</figure>

  <h3>Abstract</h3>
  <p><strong>Objective:</strong> This study explored and developed tools for early identification of depression concerns among patients with cancer by leveraging patient messages sent through a secure portal.</p>

  <p><strong>Materials and Methods:</strong> We trained classifiers based on logistic regression (LR), support vector machines (SVMs), and two Bidirectional Encoder Representations from Transformers (BERT) models (original and Reddit-pretrained) on 6,600 patient messages from a cancer centre (2009-2022), annotated by healthcare professionals. Performance was compared using AUROC, and fairness and explainability were evaluated. We also examined associations with depression diagnosis and treatment.</p>

  <p><strong>Results:</strong> BERT and RedditBERT achieved AUROCs of 0.88 and 0.86, compared with 0.79 for LR and 0.83 for SVM. BERT showed larger performance differences across sex, race, and ethnicity than RedditBERT. Patients whose messages were classified as concerning were more likely to receive a depression diagnosis, antidepressant prescription, or psycho-oncology referral. Explanations from BERT and RedditBERT differed, with no clear annotator preference.</p>

  <p><strong>Discussion:</strong> BERT and RedditBERT show potential for identifying depression concerns in patient messages. However, subgroup performance disparities indicate the need for careful bias assessment and responsible deployment in clinical workflows.</p>

  <p><strong>Conclusion:</strong> This work represents a meaningful methodological step towards early identification of depression concerns in oncology care, with potential to reduce clinical burden and improve patient support.</p>
</div>
