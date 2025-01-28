---
title: ""
permalink: /research/
author_profile: true
---

# Publications and Working Papers

My research interests lie broadly at the intersection of optimization, decision-making, and machine learning. Please see my [[research statement]](/_pages/statement.pdf) here.

## 1. Wait-Less Offline Tuning and Resolving for Online Decision Making

Jingruo Sun, Wenzhi Gao, Ellen Vitercik, and Yinyu Ye, 2024, [[arXiv]](https://arxiv.org/abs/2412.09594)

<span style="font-size:85%;"> 
Online linear programming (OLP) has found broad applications in revenue management and resource allocation. State-of-the-art OLP algorithms achieve low regret by repeatedly solving linear programming (LP) subproblems that incorporate updated resource information. However, LP-based methods are computationally expensive and often inefficient for large-scale applications. In contrast, recent first-order OLP algorithms are more computationally efficient but typically suffer from worse regret guarantees. To address these shortcomings, we propose a new algorithm that combines the strengths of LP-based and first-order OLP methods. The algorithm re-solves the LP subproblems periodically at a predefined frequency f and uses the latest dual prices to guide online decision-making. In addition, a first-order method runs in parallel during each interval between LP re-solves, smoothing resource consumption. Our algorithm achieves $ \mathcal{O}(\log(T/f) + \sqrt{f}) $ regret, delivering a "wait-less" online decision-making process that balances the computational efficiency of first-order methods and the superior regret guarantee of LP-based methods. 
</span>

## 2. SAPPHIRE: Preconditioned Stochastic Variance Reduction for Faster Large-Scale Statistical Learning

Jingruo Sun, Zachary Frangella, and Madeleine Udell, 2025, [[arXiv]](https://arxiv.org/abs/2501.15941)

<span style="font-size:85%;"> 
Regularized empirical risk minimization (rERM) has become important in data-intensive fields such as genomics and advertising,
with stochastic gradient methods typically used to solve the largest problems. However, ill-conditioned objectives and non-smooth regularizers undermine the performance of traditional stochastic gradient methods, leading to slow convergence and significant computational costs. To address these challenges, we propose the $\texttt{SAPPHIRE}$ (**S**ketching-based **A**pproximations for **P**roximal **P**reconditioning and **H**essian **I**nexactness with Variance-**RE**educed Gradients) algorithm, which integrates sketch-based preconditioning to tackle ill-conditioning and uses a scaled proximal mapping to minimize the non-smooth regularizer. This stochastic variance-reduced algorithm achieves condition-number-free linear convergence to the optimum, delivering an efficient and scalable solution for ill-conditioned composite large-scale convex machine learning problems. Extensive experiments on lasso and logistic regression demonstrate that $\texttt{SAPPHIRE}$ often converges $20$ times faster than other common choices such as $\texttt{Catalyst}$, $\texttt{SAGA}$, and $\texttt{SVRG}$. This advantage persists even when the objective is non-convex or the preconditioner is infrequently updated, highlighting its robust and practical effectiveness. 
</span>

## 3. Convergence of the Deep Galerkin Method for Mean Field Control Problems

William Hofgard, Jingruo Sun, and Asaf Cohen, 2023, [[arXiv]](https://arxiv.org/abs/2405.13346)

<span style="font-size:85%;"> 
We establish the convergence of the deep Galerkin method (DGM), a deep learning-based scheme for solving high-dimensional nonlinear PDEs, for Hamilton-Jacobi-Bellman (HJB) equations that arise from the study of mean field control problems (MFCPs). Based on a recent characterization of the value function of the MFCP as the unique viscosity solution of an HJB equation on the simplex, we establish both an existence and convergence result for the DGM. First, we show that the loss functional of the DGM can be made arbitrarily small given that the value function of the MFCP possesses sufficient regularity. Then, we show that if the loss functional of the DGM converges to zero, the corresponding neural network approximators must converge uniformly to the true value function on the simplex. We also provide numerical experiments demonstrating the DGM's ability to generalize to high-dimensional HJB equations.
</span>
