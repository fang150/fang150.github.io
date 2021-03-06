---
title: "Placeholder1."
collection: publications
permalink: /publication/2020-12-01-SC20
excerpt: 'Distributed Second Order Optimizer for Multiclass Classification Problems.'
date: 2020-12-01
venue: 'Proceedings of the ACM/IEEE Supercomputing Conference'
paperurl: 'https://arxiv.org/pdf/1807.07132.pdf'
citation: #'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---
First-order optimization methods, such as stochastic gradient descent
(SGD) and its variants, are widely used in machine learning applications
due to their simplicity and low per-iteration costs. However, they often
require larger numbers of iterations, with associated communication costs
in distributed environments. In contrast, Newton-type methods, while
having higher per-iteration costs, typically require a significantly smaller
number of iterations, which directly translates to reduced communication
costs.
In this paper, we present a novel distributed optimizer for classification
problems, which integrates a GPU-accelerated Newton-type solver with
the global consensus formulation of Alternating Direction of Method Multipliers (ADMM). By leveraging the communication efficiency of ADMM,
GPU-accelerated inexact-Newton solver, and an effective spectral penalty
parameter selection strategy, we show that our proposed method (i) yields
better generalization performance on several classification problems; (ii)
significantly outperforms state-of-the-art methods in distributed time to
solution; and (iii) offers better scaling on large distributed platforms.

[Download paper here](https://arxiv.org/pdf/1807.07132.pdf)

