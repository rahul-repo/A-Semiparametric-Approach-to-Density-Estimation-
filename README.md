# A Semiparametric Approach to Density Estimation

## Overview

This project is a group academic study on semiparametric density estimation, combining parametric modeling with nonparametric kernel density estimation. The objective is to develop a flexible density estimator that balances structural assumptions with data-driven adaptability.

The study explores a convex combination framework integrating maximum likelihood estimation and kernel density estimation.

---

## Model Framework

The semiparametric density model is defined as:

[
g(x, \pi) = \pi f(x, \hat{\theta}) + (1 - \pi)\hat{f}(x)
]

where:

* ( f(x, \hat{\theta}) ): parametric density estimated via maximum likelihood estimation
* ( \hat{f}(x) ): kernel density estimator (KDE)
* ( \pi \in [0,1] ): mixing parameter estimated numerically

---

## Objectives

* Develop a semiparametric density estimation framework
* Combine parametric and nonparametric density estimators
* Estimate the optimal mixing parameter ( \pi )
* Analyze model flexibility and stability under different assumptions

---

## Methodology

### Parametric Component

* Maximum likelihood estimation of parametric density models

### Nonparametric Component

* Kernel density estimation (KDE)

### Mixture Model

* Convex combination of parametric and KDE components
* Numerical optimization for estimating mixing parameter ( \pi )

---

## Analysis

* Behavior of estimator under parametric vs nonparametric dominance
* Convergence properties under different assumptions
* Sensitivity analysis with respect to mixing parameter
* Comparison with standalone parametric and KDE approaches

---

## Applications

* Flexible density modeling for real-valued data
* Robust estimation under model misspecification
* Clustering and density-based analysis

---

## Tools and Technologies

* R / Python
* Kernel Density Estimation
* Maximum Likelihood Estimation
* Numerical optimization
* Statistical modeling

---

## Repository Structure

```text id="semipara_struct"
README.md
report.pdf
presentation.pdf

code/
datasets/
```

---

## Authors and Contributions

This project was completed as a group academic project under faculty supervision.

### Authors

* Rahul Ganguly
* [Other authors as listed in the project report]

---

### Individual Contributions (Rahul Ganguly)

Rahul Ganguly contributed to:

* Implementation of parametric and kernel density estimation methods
* Construction of the semiparametric mixture model
* Numerical estimation of the mixing parameter ( \pi )
* Analysis of model behavior and convergence properties
* Visualization and interpretation of density estimates
* Preparation of analytical sections of the project report

---

## Project Summary

This study develops a semiparametric density estimation framework that combines parametric structure with nonparametric flexibility, providing improved modeling capability under varying distributional assumptions.

---
