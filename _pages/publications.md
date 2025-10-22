---
layout: page
permalink: /publications/
title: Publications
description:
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>

@article{sert2025,
title = {Bayesian semi-supervised Inference via a debiased modeling approach},
journal = {Econometrics and Statistics},
year = {2025},
author = {{\bf Gözde Sert} and Abhishek Chakrabortty and Anirban Bhattacharya},
pdf={BDMI.pdf},
website={https://www.sciencedirect.com/science/article/abs/pii/S2452306225000255},
abstract={Inference in semi-supervised (SS) settings has received substantial attention in recent years due to increased relevance in modern big-data problems. In a typical SS setting, there is a much larger sized unlabeled data, containing observations only for a set of predictors, in addition to a moderately sized labeled data containing observations for both an outcome and the set of predictors. Such data arises naturally from settings where the outcome, unlike the predictors, is costly or difficult to obtain. One of the primary statistical objectives in SS settings is to explore whether parameter estimation can be improved by exploiting the unlabeled data. A novel Bayesian approach to SS inference for the population mean estimation problem is proposed. The proposed approach provides improved and optimal estimators both in terms of estimation efficiency as well as inference. The method itself has several interesting artifacts. The central idea behind the method is to model certain summary statistics of the data in a targeted manner, rather than the entire raw data itself, along with a novel Bayesian notion of debiasing. Specifying appropriate summary statistics crucially relies on a debiased representation of the population mean that incorporates unlabeled data through a flexible nuisance function while also learning its estimation bias. Combined with careful usage of sample splitting, this debiasing approach mitigates the effect of bias due to slow rates or misspecification of the nuisance parameter from the posterior of the final parameter of interest, ensuring its robustness and efficiency. Concrete theoretical results, via Bernstein--von Mises theorems, are established, validating all claims, and are further supported through extensive numerical studies. To our knowledge, this is possibly the first work on Bayesian inference in SS settings, and its central ideas also apply more broadly to other Bayesian semi-parametric inference problems.}
}


@article{sertATE,
title = {Bayesian semiparametric causal inference:
Targeted doubly robust estimation of treatment
effects},
journal = {Submitted},
year = {2025+},
author = {{\bf Gözde Sert} and Abhishek Chakrabortty and Anirban Bhattacharya}
}
