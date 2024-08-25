---
title: "Improved Network Pruning via Similarity-Based Regularization"
collection: publications
category: pubpapers
permalink: /publication/202211-PRICAI-Pruning
date: 2022-11-04
venue: 'Pacific Rim International Conference on Artificial Intelligence(PRICAI)'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-031-20865-2_31'
---
**Authors:** Shaopu Wang, Xiaoying Li, Jiaxin Zhang, **Xiaojun Chen** & Jinqiao Shi

**KeyWords:** *Model Compressing and Pruning*

**Abstract:** Network pruning has been shown as an effective technique for compressing neural networks by removing weights directly. Although the pruned network consumes less training and inference costs, it tends to suffer from accuracy loss. Some recent works have proposed several norm-based regularization terms to improve the generalization ability of pruned networks. However, their penalty weights are usually set to a small value since improper regularization hurts performance, which limits their efficacy. In this work, we design a similarity-based regularization term named focus coefficient. Differing from previous regularization methods of directly pushing network weights towards zero, the focus coefficient encourages them to be statistically similar to zero. The loss produced by our method does not increase with the number of network parameters, which allows it easy to tune and compatible with large penalty weights. We empirically investigate the effectiveness of our proposed method with experiments on CIFAR-10/100, Tiny-ImageNet, and ImageNet. Results indicate that focus coefficient can improve model generalization performance and significantly reduce the accuracy loss encountered by ultra sparse networks.
