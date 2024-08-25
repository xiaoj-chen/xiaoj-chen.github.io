---
title: "Multi-initial-center federated learning with data distribution similarity-aware constraint"
collection: publications
category: pubpapers
permalink: /publication/202210-ICA3PP-FedDSMIC
date: 2022-10-10
venue: 'International Conference on Algorithms and Architectures for Parallel Processing(ICA3PP)'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-031-22677-9_41'
---
**Authors:** Xiaoying Li, **Xiaojun Chen**, Shaopu Wang, Yangyang Ding, Kaiyun Li

**KeyWords:** *Federeated Learning*, *Non-IID*

**Abstract:** Federated Learning (FL) has recently attracted high attention since it allows clients to collaboratively train a model while the training data remains local. However, due to the inherent heterogeneity of local data distributions, the trained model usually fails to perform well on each client. Clustered FL has emerged to tackle this issue by clustering clients with similar data distributions. However, these model-dependent clustering methods tend to perform poorly and be costly. In this work, we propose a distribution similarity-based clustered federated learning framework FedDSMIC, which clusters clients by detecting the client-level underlying data distribution based on the model’s memory of training data. Furthermore, we extend the assumption about data distribution to a more realistic cluster structure. The center models are learned as good initial points to obtain common data properties in the cluster. Each client in a cluster gets a more personalized model by performing one step of gradient descent from the initial point. The empirical evaluation on real-world datasets shows that FedDSMIC outperforms popular state-of-the-art federated learning algorithms while keeping the lowest communication overhead.
