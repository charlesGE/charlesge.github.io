---
layout: page
title: Publications
permalink: /publications/
---


<style>body {text-align: justify}</style>

\* denotes equal contributions.

# [Understanding Adam Requires Better Rotation Dependent Assumptions](Understanding Adam Requires Better Rotation Dependent Assumptions)
Tianyue H. Zhang\*, Alan Miligan\*, Lucas Maes\*, Alexia Jolicoeur-Martineau, Ioannis Mitliagkas, Damien Scieur, Simon Lacoste-Julien, **Charles Guille-Escuret**.

Presented at NeurIPS 2025.

*Short summary: we conduct a large scale empirical experiment on the relationship between Adam's performance and the parameter basis. We find that 
under random rotation of the basis, Adam's performance degrade severly. This suggest that Adam's de-facto dominance is tied to its ability to leverage
properties of the standard basis. Consequently, understanding Adam requires rotation-dependent assumptions capable of capturing these properties. We 
find that existing rotation-dependent in the literature do not adequately align with the performance of Adam.* 

# [Expecting The Unexpected: Towards Broad Out-Of-Distribution Detection](https://arxiv.org/abs/2308.11480)
**Charles Guille-Escuret**, Pierre-André Noel, David Vazquez, Ioannis
Mitliagkas, Joao Monteiro.

Presented at NeurIPS 2024.

*Short summary: OOD detection methods have historically focused on the detection of samples from novel classes. Some parallel work have independently tackled the detection of adversarial samples or generated images. In this work, we introduce the benchmark BROAD for the detection of 5 different types of distribution shifts. We show that existing methods perform unreliably across novel distribution shift types, and propose an ensemble method which achieves significant gains in terms of averaged detection AUC.*

# [From Conformal Predictions to Confidence Regions](https://arxiv.org/abs/2405.18601)
**Charles Guille-Escuret**, Eugène Ndiaye.

ArXiv.

*Short summary: we improve the RII method for constructing confidence regions in the finite sample regime, with minimal assumptions on the noise. 
Our approach leverages conformal prediction, granting flexibility in coverage compared to the residual intervals of RII. We derive three different
coverage guarantees depending on the assumptions on the data and/or conformal prediction algorithm.*

# [Finite Sample Confidence Regions for Linear Regression Parameters Using Arbitrary Predictors](https://arxiv.org/abs/2401.15254)
**Charles Guille-Escuret**, Eugène Ndiaye.

ArXiv.

*Short summary: we tackle the hard task of constructing confidence regions on the parameters of a model (e.g., linear) with strict coverage guarantees,
in the finite sample regime and without any strong assumption on the noise. Our method leverages the prediction of any arbitrary predictor, and 
produces the confidence region as the feasible set of a simple Mixed Integer Linear Program.*

# [No Wrong Turns: The Simple Geometry Of Neural Networks Optimization Paths](https://arxiv.org/abs/2306.11922)
**Charles Guille-Escuret**\*, Hiroki Naganuma\*, Kilian Fatras, Ioannis Mitliagkas.

Presented at ICML 2024.

*Short summary: in this work, we demonstrate surprising simple geometrical properties of the neural loss landscape through 
empirical experiment in a large variety of settings. We find links between these properties and empirical practice such as learning rate schedule, 
and discuss the impact of our findings for optimization.*

# [CADet: Fully Self-Supervised Anomaly Detection With Contrastive Learning](https://arxiv.org/abs/2210.01742)
**Charles Guille-Escuret**, Pau Rodriguez, David Vazquez, Ioannis Mitliagkas, Joao Monteiro.

Presented at NeurIPS 2023.

*Short summary: in this work, we explore applications of self-supervised contrastive learning to the simultaneous detection
of adversarial samples and unseen classes on images. Our method is inspired by the efficiency of MMD two-sample test in
discriminating   distributions.*

# [Towards Out-of-Distribution Adversarial Robustness](https://arxiv.org/abs/2210.03150)
Adam Ibrahim, **Charles Guille-Escuret**, Ioannis Mitliagkas, Irina Rish, David Krueger, Pouya Bashivan.

ArXiv. Subset presented at ICML 2022 New Frontiers In Adversarial Machine Learning Workshop.

*Short summary: adversarial robustness to a type of attack often does not transfer to other attacks, which substantially undermines the efficiency of
current methods. In this work, we view adversarial attacks as a type of distributional shift, and explore the use of the
Risk Extrapolation (REx), an out-of-distribution robustness method. Compared to existing works, we achieve better worst-case accuracy both
on the set of attacks seen during training and on a held-out set of attacks only seen at test time.*

# [Prediction of Lightning Currents on Fastening Assemblies of an Aircraft Fuel Tank with Machine Learning Methods](https://ieeexplore.ieee.org/document/10109271)
Paul Monferran\*, **Charles Guille-Escuret**\*, Christophe Guiffaut, Alain Reinex.

Published in IEEE Transactions on Electromagnetic Compatibility.

*Short summary: the precise prediction of currents on the fastening assemblies is an important challenge for the aircraft industry.
These predictions are usually performed through very computationally expensive simulations. In this work,
we use well-known machine learning methods such as XGBoost to perform accurate predictions at a small fraction
of the computational cost.*

# [Gradient Descent Is Optimal Under Lower Restricted Secant Inequality And Upper Error Bound](https://arxiv.org/abs/2203.00342)
**Charles Guille-Escuret**, Adam Ibrahim, Baptiste Goujaud, Ioannis Mitliagkas.

Presented at NeurIPS 2022.

*Short summary: previous works have outlined the unreliability of smoothness and strong-convexity as complexity metrics for the study of
first-order optimization, and proposed alternative conditions. We show that under a pair of such alternatives, gradient descent is exactly
optimal (not even up to a constant). Moreover, we introduce experiments showing that these conditions are empirically relevant to the optimization
of neural networks.*

# [A Study of Condition Numbers for First-Order Optimization](https://arxiv.org/abs/2012.05782)
**Charles Guille-Escuret**\*, Baptiste Goujaud\*, Manuela Girotti, Ioannis Mitliagkas.

Presented at AISTATS 2021. A subset was presented at NeurIPS 2020 Optimization for Machine Learning Workshop where it received the best student paper award.

*Short summary: In this work, we highlight and study pathological behaviors exposed by smoothness and strong-convexity when used as complexity metrics
for first-order optimization. We analyze how such phenomenons undermines the results theoretically derived under these conditions. Furthermore, we introduce a set of
alternative conditions which we show to be robust to these type of pathological behaviors, and for which we derive basic implications and convergence guarantees.*

# [InsectUp: Crowdsourcing Insect Observations to Assess Demographic Shifts and Improve Classification](https://arxiv.org/abs/1906.11898)
Léonard Boussioux, Tomás Giro-Larraz, **Charles Guille-Escuret**, Mehdi Cherti, Balázs Kégl.

Presented at ICML 2019 Workshop on AI for Social Good and ICCV 2019 Workshop on Wildlife Conservation.

*Short summary: insect populations are a major indicator of biodiversity. However, their assessment is severly limited by the difficulty of collecting data
at sufficient scale. In this work, we propose a method to leverage observations from bystanders, hikers and citizen scientists to foster environmental research.
Moreover, we show that their is indeed interest from both sides in such collaboration.*

