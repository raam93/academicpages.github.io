---
title: "Diverse Counterfactual Explanations (DiCE) for any machine learning model"
excerpt: "*How to explain a machine learning model such that the explanation is truthful to the model and yet interpretable to people?*<br/><img src='/images/dice_small.gif'>" 
collection: projects
---

# Diverse Counterfactual Explanations (DiCE) for any machine learning model

## Abstract:
Post-hoc explanations of machine learning models are crucial for people to understand and act on algorithmic predictions. An intriguing class of explanations is through counterfactuals, hypothetical examples that show people how to obtain a different prediction. We posit that effective counterfactual explanations should satisfy two properties: feasibility of the counterfactual actions given user context and constraints, and diversity among the counterfactuals presented. To this end, we propose a framework for generating and evaluating a diverse set of counterfactual explanations based on determinantal point processes. To evaluate the actionability of counterfactuals, we provide metrics that enable comparison of counterfactual-based methods to other local explanation methods. We further address necessary tradeoffs and point to causal implications in optimizing for counterfactuals. Our experiments on four real-world datasets show that our framework can generate a set of counterfactuals that are diverse and well approximate local decision boundaries, outperforming prior approaches to generating diverse counterfactuals. We provide an implementation of the framework at [https://github.com/microsoft/DiCE](https://github.com/microsoft/DiCE).

## Publication:
* __Ramaravind Kommiya Mothilal__, Amit Sharma, and Chenhao Tan. ["Explaining machine learning classifiers through diverse counterfactual explanations."](https://arxiv.org/pdf/1905.07697.pdf) In Proceedings of the 2020 Conference on Fairness, Accountability, and Transparency (FAccT 2020), pp. 607-617. 2020.

[[code]](https://github.com/microsoft/DiCE) [[blog]](https://www.microsoft.com/en-us/research/blog/open-source-library-provides-explanation-for-machine-learning-through-diverse-counterfactuals/) [[video]](https://www.youtube.com/watch?v=zj2NliGD0Lg)

<img src='/images/dice-example.png'>


