---
title: "EaSTFLy: Efficient and secure ternary federated learning"
collection: publications
category: pubpapers
permalink: /publication/202007-CS-EaSTFLy
date: 2020-07-01
venue: 'Computers & Security'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0167404820300985'
---
**Authors:** Ye Dong, **Xiaojun Chen**, Liyan Shen, and Dakui Wang

**KeyWords:** *Federated Learning*, *Binary Neural Network*, *Secret Sharing*

**Abstract:** Privacy-preserving machine learning allows multiple parties to perform distributed data analytics while guaranteeing individual privacy. In this area, researchers have proposed many schemes that combine machine learning with privacy-preserving technologies. But these works have shortcomings in terms of efficiency. Meanwhile, federated learning has received widespread attention due to its ability to update parameters without collecting users’ raw data, but this method is short in communications and privacy. Recently, ternary gradients federated learning(TernGrad) has been proposed to reduce the communications, but it is still to various security and privacy threats.

In this paper, firstly, we analyze the privacy leakages of TernGrad. Then, we present our solution-EaSTFLy to solve the privacy issue. More concretely, in EaSTFLy, we combine TernGrad with secret sharing and homomorphic encryption to design our privacy-preserving protocols against semi-honest adversary. In addition, we optimize our protocols via SIMD. Compared to prior works on floating-point gradients, our protocols are more efficient in communication and computation overheads, and the accuracy is as high as the plaintext ternary federated learning. To our best knowledge, this is the first research combining ternary federated learning with privacy-preserving technologies. Finally, we evaluate our experiments to show improvements.
