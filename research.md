---
layout: page
title: Research
subtitle: 
---

**Expert-Supervised Reinforcement Learning for Offline Policy Learning and Evaluation**: [pdf](https://arxiv.org/abs/2006.13189), [code](https://github.com/asonabend/ESRL), [video](https://www.youtube.com/watch?v=2f9h1kjfdCM&t=15s).

Offline Reinforcement Learning (RL) is a promising approach for learning optimal policies in environments where direct exploration is expensive or unfeasible. However, the adoption of such policies in practice is often challenging, as they are hard to interpret within the application context, and lack measures of uncertainty for the learned policy value and its decisions. To overcome these issues, we propose an Expert-Supervised RL (ESRL) framework which uses uncertainty quantification for offline policy learning. In particular, we have three contributions: 1) the method can learn safe and optimal policies through hypothesis testing, 2) ESRL allows for different levels of risk aversion within the application context, and finally, 3) we propose a way to interpret ESRL's policy at every state through posterior distributions, and use this framework to compute off-policy value function posteriors. We provide theoretical guarantees for our estimators and regret bounds consistent with Posterior Sampling for RL (PSRL) that account for any risk aversion threshold. We further propose an offline version of PSRL as a special case of ESRL.

**Automated ICD coding via unsupervised knowledge integration (UNITE)**: [pdf](https://www.sciencedirect.com/science/article/abs/pii/S1386505619313024)


Accurate coding is critical for medical billing and electronic medical record (EMR)-based research. Recent research has been focused on developing supervised methods to automatically assign International Classification of Diseases (ICD) codes from clinical notes. However, supervised approaches rely on ICD code data stored in the hospital EMR system and is subject to bias rising from the practice and coding behavior. Consequently, portability of trained supervised algorithms to external EMR systems may suffer.

Method
We developed an unsupervised knowledge integration (UNITE) algorithm to automatically assign ICD codes for a specific disease by analyzing clinical narrative notes via semantic relevance assessment. The algorithm was validated using coded ICD data for 6 diseases from Partners HealthCare (PHS) Biobank and Medical Information Mart for Intensive Care (MIMIC-III). We compared the performance of UNITE against penalized logistic regression (LR), topic modeling, and neural network models within each EMR system. We additionally evaluated the portability of UNITE by training at PHS Biobank and validating at MIMIC-III, and vice versa.

Results
UNITE achieved an averaged AUC of 0.91 at PHS and 0.92 at MIMIC over 6 diseases, comparable to LR and MLP. It had substantially better performance than topic models. In regards to portability, the performance of UNITE was consistent across different EMR systems, superior to LR, topic models and neural network models.

Conclusion
UNITE accurately assigns ICD code in EMR without requiring human labor, and has major advantages over commonly used machine learning approaches. In addition, the UNITE attained stable performance and high portability across EMRs in different institutions.


 **Integrating questionnaire measures for transdiagnostic psychiatric phenotyping using word2vec**: [pdf](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0230663)
 
 
 Background
Recent initiatives in psychiatry emphasize the utility of characterizing psychiatric symptoms in a multidimensional manner. However, strategies for applying standard self-report scales for multiaxial assessment have not been well-studied, particularly where the aim is to support both categorical and dimensional phenotypes.

Methods
We propose a method for applying natural language processing to derive dimensional measures of psychiatric symptoms from questionnaire data. We utilized nine self-report symptom measures drawn from a large cellular biobanking study that enrolled individuals with mood and psychotic disorders, as well as healthy controls. To summarize questionnaire results we used word embeddings, a technique to represent words as numeric vectors preserving semantic and syntactic meaning. A low-dimensional approximation to the embedding space was used to derive the proposed succinct summary of symptom profiles. To validate our embedding-based disease profiles, these were compared to presence or absence of axis I diagnoses derived from structured clinical interview, and to objective neurocognitive testing.

Results
Unsupervised and supervised classification to distinguish presence/absence of axis I disorders using survey-level embeddings remained discriminative, with area under the receiver operating characteristic curve up to 0.85, 95% confidence interval (CI) (0.74,0.91) using Gaussian mixture modeling, and cross-validated area under the receiver operating characteristic curve 0.91, 95% CI (0.88,0.94) using logistic regression. Derived symptom measures and estimated Research Domain Criteria scores also associated significantly with performance on neurocognitive tests.

Conclusions
Our results support the potential utility of deriving dimensional phenotypic measures in psychiatric illness through the use of word embeddings, while illustrating the challenges in identifying truly orthogonal dimensions.
