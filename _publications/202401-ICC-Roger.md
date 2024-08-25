---
title: "Roger: A Round Optimized GPU-Friendly Secure Inference Framework"
collection: publications
category: pubpapers
permalink: /publication/202301-ICC-Roger
date: 2024-01-26
venue: 'International Conference on Communications (ICC)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10623025/'
---
**Authors:** Xudong Chen, **Xiaojun Chen**, Ye Dong, Weizhan Jing, Tingyu Fan, and Qinghui Zhang

**KeyWords:** *Secure Multiparty Computation*, *Secure Model Inference*

**Abstract:** Secure neural network inference provides a promising solution to preserve the privacy of Deep Learning as a Service (DLaaS), but its substantial communication and computation overhead remain challenging. Recent works such as GForce [1] and Piranha [2] have introduced GPU-friendly secure inference protocols with improved computation efficiency, yet these approaches are either limited to supporting specialized-trained networks or expensive in communication. As a consequence, there remain potential improvements in functionalities and communication efficiency. To address the above challenges, we introduce Roger, a two-party secure inference framework with semi-honest security, designed to support general neural network inference with a reduced number of round complexity. Drawing inspiration from ABY2.0 [3], we propose the Partial-Fix technology, which fixes the share of one participant during the offline phase to improve its computation efficiency. Then, an online communication-free protocol for secure linear layer computation and a constant-round secure comparison protocol are proposed upon Partial-Fix. Implemented on top of Piranha, the experiments demonstrate that for the CIFAR10 dataset, a single inference on VGG16 requires only 0.40 seconds. In comparison to GForce (resp. Piranha), Roger at least achieves 1.20× (resp. 1.94×) improvement in LAN setting in terms of throughput.
