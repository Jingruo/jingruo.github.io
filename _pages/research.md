---
title: ""
permalink: /research/
author_profile: true
---

# Publications and Working Papers

## 1. Wait-Less Offline Tuning and Resolving for Online Decision Making

Jingruo Sun, Wenzhi Gao, Ellen Vitercik, and Yinyu Ye, [[arXiv]](https://arxiv.org/abs/2412.09594)

<span style="font-size:85%;"> 
Online linear programming (OLP) has found broad applications in revenue management and resource allocation. State-of-the-art OLP algorithms achieve low regret by repeatedly solving linear programming (LP) subproblems that incorporate updated resource information. However, LP-based methods are computationally expensive and often inefficient for large-scale applications. In contrast, recent first-order OLP algorithms are more computationally efficient but typically suffer from worse regret guarantees. To address these shortcomings, we propose a new algorithm that combines the strengths of LP-based and first-order OLP methods. The algorithm re-solves the LP subproblems periodically at a predefined frequency f and uses the latest dual prices to guide online decision-making. In addition, a first-order method runs in parallel during each interval between LP re-solves, smoothing resource consumption. Our algorithm achieves $ \mathcal{O}(\log(T/f) + \sqrt{f}) $ regret, delivering a "wait-less" online decision-making process that balances the computational efficiency of first-order methods and the superior regret guarantee of LP-based methods. 
</span>

## 2. SAPPHIRE: Preconditioned Stochastic Variance Reduction for Faster Large-Scale Statistical Learning

Jingruo Sun, Zachary Frangella, and Madeleine Udell

<span style="font-size:85%;"> 
Rapid growth of modern machine learning and statistical applications has driven increasing interest in solving high-dimensional optimization problems. However, the challenges posed by ill-conditioned, non-smooth, and large-scale optimization tasks often undermine the performance of traditional stochastic gradient methods, leading to slow convergence and significant computational inefficiencies. 
To address these challenges, we propose the SAPPHIRE (**S**ketching-based **A**pproximations for **P**roximal **P**reconditioning and **H**essian **I**nexactness with Variance-**R**educed Gradi**E**nts) algorithm. It integrates advanced sketching-based preconditioning techniques to tackle ill-conditioning and scaled proximal mapping to stabilize the optimization process. We demonstrate that our algorithm achieves a global linear convergence under quadratic regularity. Empirical evaluations show that SAPPHIRE outperforms other commonly used methods such as Catalyst, SAGA, and SVRG even with infrequent updates of preconditioners or non-convex objectives, highlighting its robustness and effectiveness. 
</span>

## 3. Convergence of the Deep Galerkin Method for Mean Field Control Problems

William Hofgard, Jingruo Sun, and Asaf Cohen, [[arXiv]](https://arxiv.org/abs/2405.13346)

<span style="font-size:85%;"> 
We establish the convergence of the deep Galerkin method (DGM), a deep learning-based scheme for solving high-dimensional nonlinear PDEs, for Hamilton-Jacobi-Bellman (HJB) equations that arise from the study of mean field control problems (MFCPs). Based on a recent characterization of the value function of the MFCP as the unique viscosity solution of an HJB equation on the simplex, we establish both an existence and convergence result for the DGM. First, we show that the loss functional of the DGM can be made arbitrarily small given that the value function of the MFCP possesses sufficient regularity. Then, we show that if the loss functional of the DGM converges to zero, the corresponding neural network approximators must converge uniformly to the true value function on the simplex. We also provide numerical experiments demonstrating the DGM's ability to generalize to high-dimensional HJB equations.
</span>

## 4. Importance-Weighted Sampling Enhanced VAE for MIRT Model

Jingruo Sun and Gongjun Xu

<span style="font-size:85%;"> 
Multidimensional Item Response Theory provides an ideal foundation for modeling performance in complex domains, taking into account multiple basic abilities simultaneously, and representing different mixtures of the abilities required for different test items. However, with the increasing size of modern assessment data, conventional estimation methods become computationally demanding, and hence they are not scalable to big data. To tackle this challenge, we present a novel approach utilizing importance-weighted sampling
enhanced Variational Autoencoder on logistic models. We leverage the power of variational inference from the field of machine learning to effectively approximate the elusive marginal likelihood. We further enhance our method by using importance-weighted samples to yield a superior log-likelihood approximation.
</span>
