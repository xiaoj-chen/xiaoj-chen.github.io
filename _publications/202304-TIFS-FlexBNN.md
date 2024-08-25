---
title: "FLEXBNN: Fast Private Binary Neural Network Inference with Flexible Bit-Width"
collection: publications
category: pubpapers
permalink: /publication/202304-TIFS-FlexBNN
date: 2023-04-06
venue: 'IEEE Transactions on Information Forensics and Security(TIFS)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10093909'
---
**Authors:** Ye Dong, **Xiaojun Chen**, Xiangfu Song, Kaiyun Li

**KeyWords:** *Secure Multiparty Computation*, *Private Binary Neural Network Inference*

**Abstract:** Advancements in deep learning enable neural network (NN) inference to be a service, but service providers and clients want to keep their inputs secret for privacy protection. Private Inference is the task of evaluating NN without leaking private inputs. Existing secure multiparty computation (MPC)-based solutions mainly focus on fixed bit-width methodology, such as 32 and 64 bits. Binary Neural Network (BNN) is efficient when evaluated in MPC and has achieved reasonable accuracy for commonly used datasets, but prior private BNN inference solutions, which focus on Boolean Circuits , are still costly in communication and run-time. In this paper, we introduce FLEXBNN, a fast private BNN inference framework using three-party computation (3PC) in Arithmetic Circuits against semi-honest adversaries with honest-majority. In FLEXBNN, we propose to employ flexible and small bit-width equipped with a seamless bit-width conversion method and design several specific optimizations towards the basic operations: i) We propose bit-width determination methods for Matrix Multiplication and Sign-based Activation function. ii) We integrate Batch Normalization and Max-Pooling into the Sign-based Activation function for better efficiency. iii) More importantly, we achieve seamless bit-width conversion within the Sign-based Activation function with no additional cost. Extensive experiments illustrate that FLEXBNN outperforms state-of-the-art solutions in communication, run-time, and scalability. On average, FLEXBNN is 11× faster than XONN (USENIX Security’ 19) in LAN, 46× (resp. 9.3×) faster than QUOTIENT (ACM CCS’19) in LAN (resp. WAN), 10× faster than BANNERS (ACM IH&MMSec’21) in LAN, and 1.1-2.9× (resp. 1.5-2.7×) faster than FALCON (semi-honest, PoPETs’21) in LAN (resp. WAN), and improves the respective communication by 500×, 127×, and 1.3-1.5× compared to XONN, BANNERS, and FALCON.
