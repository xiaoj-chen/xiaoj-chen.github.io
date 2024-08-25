---
title: "Efficient Byzantine-Resilient Stochastic Gradient Descent"
collection: publications
category: pubpapers
permalink: /publication/202108-IJCAIW-Byzantin-Resilient
date: 2021-08-17
venue: 'International Workshop on Federated and Transfer Learning for Data Sparsity and Confidentiality in Conjunction with IJCAI(Workshop in IJCAI)'
paperurl: 'https://arxiv.org/abs/2108.06658'
---
**Authors:** Kaiyun Li, **Xiaojun Chen**, Ye Dong, Peng Zhang, Dakui Wang, and Shuai Zeng

**KeyWords:** *Federated Learning*, *Byzantine Attacks*

**Abstract:** Distributed Learning often suffers from Byzantine failures, and there have been a number of works studying the problem of distributed stochastic optimization under Byzantine failures, where only a portion of workers, instead of all the workers in a distributed learning system, compute stochastic gradients at each iteration. These methods, albeit workable under Byzantine failures, have the shortcomings of either a sub-optimal convergence rate or high computation cost. To this end, we propose a new Byzantine-resilient stochastic gradient descent algorithm (BrSGD for short) which is provably robust against Byzantine failures. BrSGD obtains the optimal statistical performance and efficient computation simultaneously. In particular, BrSGD can achieve an order-optimal statistical error rate for strongly convex loss functions. The computation complexity of BrSGD is O(md), where d is the model dimension and m is the number of machines. Experimental results show that BrSGD can obtain competitive results compared with non-Byzantine machines in terms of effectiveness and convergence.
