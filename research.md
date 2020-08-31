---
layout: page
title: Research
subtitle: 
---

# Reinforcement Learning

I'm interested in developing reinforcement learning (RL) methods that can adapt to challenging real-data settings such as healthcare. In particular I'm interested in offline RL for learning optimal policies in environments where direct exploration is expensive or unfeasible, settings when the Markovian assumption is violated such as in the dynamical treament regimen setting, where all medical history is relevant, and when not all rewards are observed which is often the case in electronic health records.


__Aaron Sonabend W__, Junwei Lu, Leo A. Celi, Tianxi Cai, Peter Szolovits **Expert-Supervised Reinforcement Learning for Offline Policy Learning and Evaluation** ([pdf](https://arxiv.org/abs/2006.13189), [code](https://github.com/asonabend/ESRL), [video](https://www.youtube.com/watch?v=2f9h1kjfdCM&t=15s)).

<div style="clear: both;">
  <div style="float: left; margin-left 1em;">
    <img src="https://asonabend.github.io/imgs/ESRL.png" width="130" height="90" alt="">

  </div>
  <div>
    <p>We develop an RL method which uses uncertainty quantification for offline policy learning. 1) the method can learn safe and optimal policies through hypothesis testing, 2) allows for different levels of risk aversion within the application context, and 3) yields interpretable acxtions at every state through posterior distributions. We also propose using this framework to compute off-policy value function posteriors. We provide theoretical guarantees for our estimators and regret bounds.
</p>
  </div>
</div>

# Phenotyping with Natural Language Processing

I'm interested in using NLP for automatic diagnosing, this is a hard problem where usually there is a lack of labels, therefore unsupervisde phenotyping methods such as UNITE are highly attractive and generalize well across ddatasets. Additionally, I'm interested in using natural language to discover patters behind psychiatric behavior. 

__Aaron Sonabend W__, Winston Cai, Yuri Ahuja, Ashwin Ananthakrishnan, Zongqi Xia, Sheng Yu, Chuan Hong **Automated ICD coding via unsupervised knowledge integration (UNITE)**, [International Journal of Medical Informatics](https://www.sciencedirect.com/science/article/abs/pii/S1386505619313024).

<div style="clear: both;">
  <div style="float: left; margin-left 1em;">
    <img src="https://asonabend.github.io/imgs/UNITE.png" width="130" height="90" alt="">
  </div>
  <div>
    <p>We developed an unsupervised knowledge integration (UNITE) algorithm to automatically assign phenotype codes for a specific disease by analyzing clinical narrative notes via semantic relevance assessment. UNITE has substantially better performance than unsupervised methods like topic models, and the performance is consistent across different electronic medical records (EMR) systems, which is often an issue with deep learning models. It also requires no human annotation of labels which makes it robust to bias often found within EMR systems.
</p>
  </div>
</div>


__Aaron Sonabend W.__, Amelia M. Pellegrini, Stephanie Chan, Hannah E. Brown, James N. Rosenquist, Pieter J. Vuijk, Alysa E. Doyle, Roy H. Perlis , Tianxi Cai **Integrating questionnaire measures for transdiagnostic psychiatric phenotyping using _word2vec_**, [PLOS ONE](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0230663).
 
 <div style="clear: both;">
  <div style="float: left; margin-left 1em;">
    <img src="https://asonabend.github.io/imgs/clusters.png" width="130" height="90" alt="">
  </div>
  <div>
    <p>We propose a method for applying natural language processing to derive dimensional measures of psychiatric symptoms from questionnaire data. We used 9 symptom measures from cellular biobanking study that enrolled individuals with mood and psychotic disorders, as well as healthy controls. A low-dimensional approximation to the embedding space was used to derive succinct summary of symptom profiles. To validate our embedding-based disease profiles, these were compared to presence or absence of axis I diagnoses derived from structured clinical interview, and to objective neurocognitive testing. We also found that unsupervised clustering of these low-dimensional profiles discriminate well between cases and controls. Our derived symptom measures and estimated Research Domain Criteria scores also associated significantly with performance on neurocognitive tests.
</p>
  </div>
</div>
 

