---
title: ""
permalink: /research/
author_profile: true
---

# Publications

## Goedel-Prover-V2: Scaling Formal Theorem Proving with Scaffolded Data Synthesis and Self-Correction

Yong Lin, Shange Tang, Bohan Lyu, Ziran Yang, Jui-Hui Chung, Haoyu Zhao, Lai Jiang, Yihan Geng, Jiawei Ge, **Jingruo Sun**, Jiayun Wu, Jiri Gesi, Ximing Lu, David Acuna, Kaiyu Yang, Hongzhou Lin, Yejin Choi, Danqi Chen, Sanjeev Arora, and Chi Jin

**International Conference on Learning Representations (ICLR), 2026**

**International Conference on Machine Learning (ICML) AI4MATH Workshop (Oral), 2025**

[Paper](https://arxiv.org/abs/2508.03613) · [Code](https://github.com/Goedel-LM/Goedel-Prover-V2)

- We introduce open-source language models for theorem proving in Lean, combining scaffolded data synthesis, verifier-guided self-correction, and checkpoint averaging.
  
- In self-correction mode, the 32B model achieves 90.4% pass@32 on MiniF2F and solves 86 PutnamBench problems at pass@184.

## Wait-Less Offline Tuning and Re-solving for Online Decision Making

**Jingruo Sun**, Wenzhi Gao, Ellen Vitercik, and Yinyu Ye

**International Conference on Machine Learning (ICML), 2025**

[Paper](https://proceedings.mlr.press/v267/sun25e.html) · [arXiv](https://arxiv.org/abs/2412.09594) · [Code](https://github.com/Jingruo/Wait-Less-Online-Decision-Making)

- We balance decision quality and computation in online resource allocation by coupling periodic linear programming (LP) re-solving with inexpensive first-order updates. The two components exchange information through a feedback loop, enabling immediate decisions without solving a new LP for each arrival.
  
- A unified analysis of LP-based and first-order methods quantifies how re-solving frequency controls regret under the stochastic input model. Experiments demonstrate at least a 10-fold reduction in regret relative to first-order baselines and 100-fold speedups over LP-based baselines.


## SAPPHIRE: Preconditioned Stochastic Variance Reduction for Faster Large-Scale Statistical Learning

**Jingruo Sun**, Zachary Frangella, and Madeleine Udell

**SIAM Journal on Mathematics of Data Science (SIMODS) · Accepted**

[arXiv](https://arxiv.org/abs/2501.15941) · [Code](https://github.com/udellgroup/sapphire)

- We develop a stochastic optimization method that combines sketched curvature information with variance-reduced proximal updates to accelerate regularized learning with ill-conditioned objectives and nonsmooth penalties.

- Establishes global convergence and a local linear rate independent of the condition number. Converges 20× faster than Catalyst, SAGA, and SVRG on lasso and logistic-regression tasks.

## Convergence of the Deep Galerkin Method for Finite State Mean Field Control Problems

William Hofgard, **Jingruo Sun**, and Asaf Cohen

**SIAM Journal on Mathematics of Data Science (SIMODS) · Accepted**

[arXiv](https://arxiv.org/abs/2405.13346)

- We reformulate the Deep Galerkin Method (DGM) using a uniform-residual ($L^{\infty}$) loss for the nonlinear Hamilton–Jacobi–Bellman equations in finite-state mean field control.

- Under the stated regularity assumptions, we prove that the DGM loss can be made arbitrarily small and that any sequence of neural-network approximations with vanishing loss converges uniformly to the value function.
