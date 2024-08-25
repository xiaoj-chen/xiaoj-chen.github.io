---
title: "Efficient and Secure Federated Learning Based on Secret Sharing and Gradients Selection"
collection: publications
category: pubpapers
permalink: /publication/202007-JCRD-FLSS
date: 2020-07-01
venue: 'Journal of Computer Research and Development(计算机研究与发展)'
paperurl: 'https://crad.ict.ac.cn/en/article/doi/10.7544/issn1000-1239.2020.20200463'
---
**Authors:** Ye Dong, Wei Hou, **Xiaojun Chen**, Shai Zeng

**KeyWords:** *Federated Learning*, *Secret Sharing*

**Abstract:** In recent years, federated learning (FL) has been an emerging collaborative machine learning method where distributed users can train various models by only sharing gradients. To prevent privacy leakages from gradients, secure multi-party computation (MPC) has been considered as a promising guarantee recently. Meanwhile, some researchers proposed the Top-K gradients selection algorithm to reduce the traffic for synchronizing gradients among distributed users. However, there are few works that can balance the advantages of the two areas at present. We combine secret sharing with Top-K gradients selection to design efficient and secure federated learning protocols, so that we can cut down the communication overheads and improve the efficiency during the training phase while guaranteeing the users privacy and data security. Also, we propose an efficient method to construct message authentication code (MAC) to verify the validity of the aggregated results from the servers. And the communication overheads introduced by the MAC is small and independent of the number of shared gradients. Besides, we implement a prototype system. Compared with the plaintext training, on the one hand, our secure techniques introduce small additional overheads in communication and computation; On the other hand, we achieve the same level of accuracy as the plaintext training.
