---
title: "Meteor: Improved Secure 3-Party Neural Network Inference with Reducing Online Communication Costs"
collection: publications
category: pubpapers
permalink: /publication/202301-WWW-Meteor
date: 2023-01-25
venue: 'The 2023 ACM Web Conference(WWW)'
paperurl: 'https://eprint.iacr.org/2023/100'
---
**Authors:** Ye Dong, **Xiaojun Chen**, Weizhan Jing, Kaiyun Li, Weiping Wang

**KeyWords:** *Secure Multiparty Computation*, *Private Neural Network Inference*

**Abstract:** Secure neural network inference has been a promising solution to private Deep-Learning-as-a-Service, which enables the service provider and user to execute neural network inference without revealing their private inputs. However, the expensive overhead of current schemes is still an obstacle when applied in real applications. In this work, we present \textsc{Meteor}, an online communication-efficient and fast secure 3-party computation neural network inference system aginst semi-honest adversary in honest-majority. The main contributions of \textsc{Meteor} are two-fold: \romannumeral1) We propose a new and improved 3-party secret sharing scheme stemming from the \textit{linearity} of replicated secret sharing, and design efficient protocols for the basic cryptographic primitives, including linear operations, multiplication, most significant bit extraction, and multiplexer. \romannumeral2) Furthermore, we build efficient and secure blocks for the widely used neural network operators such as Matrix Multiplication, ReLU, and Maxpool, along with exploiting several specific optimizations for better efficiency. Our total communication with the setup phase is a little larger than SecureNN (PoPETs'19) and \textsc{Falcon} (PoPETs'21), two state-of-the-art solutions, but the gap is not significant when the online phase must be optimized as a priority. Using \textsc{Meteor}, we perform extensive evaluations on various neural networks. Compared to SecureNN and \textsc{Falcon}, we reduce the online communication costs by up to $25.6\times$ and $1.5\times$, and improve the running-time by at most $9.8\times$ (resp. $8.1\times$) and $1.5\times$ (resp. $2.1\times$) in LAN (resp. WAN) for the online inference.
