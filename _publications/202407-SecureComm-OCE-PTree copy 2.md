---
title: "OCE-PTree: An Online Communication Efficient Privacy–preserving Decision Tree Evaluation (ACCEPTED)"
collection: publications
category: pubpapers
permalink: /publication/202403-SecureCOMM-OCE-PTree
date: 2024-07-14
venue: 'EAI SecureComm 2024'
paperurl: ''

---
**Authors:**  **Xiaojun Chen**, Weizhan Jing etc.

**KeyWords:** *Secure Multiparty Computation*, *Secure Model Inference*

**Abstract:** Privacy-preserving Decision Tree
Evaluation (PDTE) is a promising solution to private Machine-Learning-as-a-Service, which allows clients to classify their data using a tree model from model owners and only reveals the inference result to clients. However, the expensive overhead of current schemes is still an obstacle in practical applications.

In this work, we present OCE-PTree, an online communication efficient privacy-preserving decision tree evaluation protocol with semi-honest security. OCE-PTree's main contributions are two-fold: i) We use vector inner product, combined with additive secret sharing and mask secret sharing, to achieve efficient feature selection. ii) We propose a path evaluation protocol based on One-Time Truth Table (OTTT) for reducing communication costs in the online phase.

Experimental results on various decision trees and datasets demonstrate that our online communication costs is less than the work of Ma $\textit{et al.}$ (NDSS'21) and Mostree (ACSAC’23), two state-of-the-art solutions. To be more specific, we reduce the online communication by upto 7-12$\times$, and improve the online running-time by at most 2.3$\times$, 1.5$\times$ and 1.3$\times$ in LAN, MAN and WAN compared to the work of Ma $\textit{et al.}$. In addition, we reduce the online communication by upto 1.7$\times$, and improve the online running-time by at most 25$\times$ in LAN, MAN and WAN compared to Mostree.
