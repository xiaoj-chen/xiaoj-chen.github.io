---
title: "Comet: Communication-Efficient Batch Secure Three-Party Neural Network Inference with Client-Aiding"
collection: publications
category: pubpapers
permalink: /publication/202301-ICC-Comet
date: 2024-01-26
venue: 'International Conference on Communications (ICC)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10623025/'
---
**Authors:** Tingyu Fan, **Xiaojun Chen**, Ye Dong, Xudong Chen, and Weizhan Jing

**KeyWords:** *Secure Multiparty Computation*, *Secure Model Inference*

**Abstract:** Secure neural network inference enables server (model provider) and client to perform neural network inference without leaking their private inputs. Existing SOTA three-party computation (3PC) inference works emerge challenges on two fronts: i) GPU-accelerated CryptGPU (S&P'21) and P-FALCON (USENIX Security'22) face challenges related to high communication overhead. ii) communication-efficient Meteor(www'23) raises more computation burden and GPU memory usage. These challenges result in lower efficiency when handling large-scale batch inference requests on resource-constrained devices. In this work, we propose Comet,a communication-efficient batch secure three-party inference framework with client-aiding, which achieves semi-honest security in honest majority without collusion between the client and the servers. First, we propose client-aided sharing semantics, which leverages client-generated random values to enhance online communication efficiency. We also design efficient 3PC protocols for neural network operators based on GPU, improving the computational efficiency of both linear and nonlinear layers. Furthermore, we address the tradeoff between communication cost and GPU memory utilization, surpassing SOTA by 1.3-1.9× in communication, 1.5-3.8× in runtime on large-scale batch inference tasks.
