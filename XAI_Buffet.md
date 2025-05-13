# Comprehensive XAI Methods List

This document categorizes and lists existing Explainable AI (XAI) methods along with their reference papers.

---

## Attribution-Based
| Method | Reference |
|--------|-----------|
| Saliency Maps | Simonyan et al., 2013 |
| Integrated Gradients | Sundararajan et al., 2017 |
| DeepLIFT | Shrikumar et al., 2017 |
| Layer-wise Relevance Propagation (LRP) | Bach et al., 2015 |
| Grad-CAM / Guided Grad-CAM | Selvaraju et al., 2017 |
| SmoothGrad | Smilkov et al., 2017 |
| SHAP | Lundberg & Lee, 2017 |
| LIME | Ribeiro et al., 2016 |
| Occlusion Sensitivity | Zeiler & Fergus, 2014 |
| Excitation Backprop | Zhang et al., 2016 |
| Class Activation Mapping (CAM) | Zhou et al., 2016 |
| Contextual Decomposition | Murdoch et al., 2018 |

## Example-Based
| Method | Reference |
|--------|-----------|
| k-Nearest Neighbors (k-NN) | Cover & Hart, 1967 |
| Influence Functions | Koh & Liang, 2017 |
| Prototype & Criticism Models | Kim et al., 2016 |
| Case-Based Reasoning | Aamodt & Plaza, 1994 |
| Representer Point Selection | Yeh et al., 2018 |
| TracIn | Pruthi et al., 2020 |
| MMD-Critic | Kim et al., 2016 |
| KNN-Shapley | Jia et al., 2019 |

## Surrogate/Approximation-Based
| Method | Reference |
|--------|-----------|
| Anchors | Ribeiro et al., 2018 |
| Decision Trees/Rules as Surrogates | Frosst & Hinton, 2017 |
| Symbolic Metamodels | Lakkaraju et al., 2016 |
| RuleFit | Friedman & Popescu, 2008 |
| Global Surrogate Models | Craven & Shavlik, 1996 |

## Intrinsic Explainability
| Method | Reference |
|--------|-----------|
| Decision Trees | Breiman et al., 1984 |
| Rule-Based Models (RIPPER, CN2) | Cohen, 1995; Clark & Niblett, 1989 |
| Linear/Logistic Regression | Cox, 1958 |
| Generalized Additive Models (GAMs) | Hastie & Tibshirani, 1990 |
| Explainable Boosting Machines (EBMs) | Nori et al., 2019 |
| Sparse Models (LASSO) | Tibshirani, 1996 |
| Bayesian Rule Lists | Letham et al., 2015 |
| Supersparse Linear Integer Models (SLIM) | Ustun & Rudin, 2016 |

## Visualization-Based
| Method | Reference |
|--------|-----------|
| Activation Maximization | Erhan et al., 2009 |
| Feature Visualization | Olah et al., 2017 |
| t-SNE/UMAP Projections | van der Maaten & Hinton, 2008; McInnes et al., 2018 |
| Filter Visualizations | Zeiler & Fergus, 2014 |
| Neuron Ablation/Importance | Morcos et al., 2018 |
| Network Dissection | Bau et al., 2017 |
| Net2Vec | Fong & Vedaldi, 2018 |
| Channel Attribution | Zhou et al., 2016 |

## Concept-Based
| Method | Reference |
|--------|-----------|
| TCAV | Kim et al., 2018 |
| Concept Bottleneck Models | Koh et al., 2020 |
| ACE | Ghorbani et al., 2019 |
| CRP | Schoenfeld et al., 2022 |

## Counterfactual/Contrastive
| Method | Reference |
|--------|-----------|
| Counterfactual Explanations | Wachter et al., 2017 |
| Contrastive Explanation Method (CEM) | Dhurandhar et al., 2018 |
| DiCE | Mothilal et al., 2020 |
| FACE | Poyiadzi et al., 2020 |
| Actionable Recourse | Ustun et al., 2019 |
| Growing Spheres | Laugel et al., 2017 |

## Attention-Based
| Method | Reference |
|--------|-----------|
| Attention Weights Visualization | Bahdanau et al., 2014 |
| Attention Rollout | Abnar & Zuidema, 2020 |
| Attention Flow | Chefer et al., 2021 |
| Gradient-based Attention | Bastings et al., 2020 |
| Attention Attribution (e.g., BertViz) | Vig, 2019 |