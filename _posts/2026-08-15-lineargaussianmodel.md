---
title: 'Linear Gaussian model'
date: 2026-08-14
permalink: /posts/2026/08/lineargaussianmodel/
share: false
tags:
  - statistics
  - linear models
---
This 


## Introduction

The linear Gaussian model is one of the fundamental models in statistical modeling. It provides a simple framework for understanding the relationship between a response variable and a set of explanatory variables under Gaussian assumptions.
In this post, we introduce the model, discuss its probabilistic formulation, derive the likelihood, and explore its connection with Bayesian inference.

## 1. The model

Consider the linear model

\\[\mathbf{y} = \mathbf{A}\mathbf{x} + \boldsymbol{\varepsilon}, \\]

where:

-  \\(\mathbf{y} \in \mathbb{R}^n\\) is the response vector,
-  \\(X \in \mathbb{R}^{n\times p}\\) is the design matrix,
-  \\(\boldsymbol{\beta} \in \mathbb{R}^p\\) is the vector of regression coefficients,
-  \\(\boldsymbol{\varepsilon}\\) is the error vector.

