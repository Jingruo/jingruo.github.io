---
title: ""
permalink: /research/
author_profile: true
---

# Publications and Working Papers

## 1. Wait-Less Offline Tuning and Resolving for Online Decision Making

Jingruo Sun, Wenzhi Gao, Ellen Vitercik, and Yinyu Ye, [[arXiv]](https://arxiv.org/abs/2412.09594)

Online linear programming (OLP) has found broad applications in revenue management and resource allocation. State-of-the-art OLP algorithms achieve low regret by repeatedly solving linear programming (LP) subproblems that incorporate updated resource information. However, LP-based methods are computationally expensive and often inefficient for large-scale applications. In contrast, recent first-order OLP algorithms are more computationally efficient but typically suffer from worse regret guarantees. To address these shortcomings, we propose a new algorithm that combines the strengths of LP-based and first-order OLP methods. The algorithm re-solves the LP subproblems periodically at a predefined frequency f and uses the latest dual prices to guide online decision-making. In addition, a first-order method runs in parallel during each interval between LP re-solves, smoothing resource consumption. Our algorithm achieves $\mathcal{O}(\log(T/f) + \sqrt{f})$ regret, delivering a "wait-less" online decision-making process that balances the computational efficiency of first-order methods and the superior regret guarantee of LP-based methods.
