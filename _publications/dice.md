---
title: "Explaining Machine Learning Classifiers through Diverse Counterfactual Examples"
collection: publications
permalink: /publication/dice
excerpt: 'Post-hoc explanations of machine learning models are crucial for people to understand and act on algorithmic predictions. An intriguing class of explanations is through counterfactuals, hypothetical examples that show people how to obtain a different prediction. We posit that effective counterfactual explanations should satisfy two properties: feasibility of the counterfactual actions given user context and constraints, and diversity among the counterfactuals presented. To this end, we propose a framework for generating and evaluating a diverse set of counterfactual explanations based on determinantal point processes.'
date: 2020-01-26
venue: 'Proceedings of the Conference on Fairness, Accountability, and Transparency.'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3351095.3372850'
citation: ''
---


[**[pdf]**](https://arxiv.org/pdf/1905.07697.pdf) [**[code]**](https://github.com/microsoft/DiCE)
### Abstract:
Post-hoc explanations of machine learning models are crucial for people to understand and act on algorithmic predictions. An intriguing class of explanations is through counterfactuals, hypothetical examples that show people how to obtain a different prediction. We posit that effective counterfactual explanations should satisfy two properties: feasibility of the counterfactual actions given user context and constraints, and diversity among the counterfactuals presented. To this end, we propose a framework for generating and evaluating a diverse set of counterfactual explanations based on determinantal point processes. To evaluate the actionability of counterfactuals, we provide metrics that enable comparison of counterfactual-based methods to other local explanation methods. We further address necessary tradeoffs and point to causal implications in optimizing for counterfactuals. Our experiments on four real-world datasets show that our framework can generate a set of counterfactuals that are diverse and well approximate local decision boundaries, outperforming prior approaches to generating diverse counterfactuals. We provide an implementation of the framework at https://github.com/microsoft/DiCE.
