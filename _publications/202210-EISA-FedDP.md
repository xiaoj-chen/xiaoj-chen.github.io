---
title: "An Efficient Federated Convolutional Neural Network Scheme with Differential Privacy"
collection: publications
category: pubpapers
permalink: /publication/202210-EISA-FedDP
date: 2022-10-29
venue: 'International Symposium on Emerging Information Security and Applications(EISA)'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-031-23098-1_11'
---
**Authors:** Dayin Zhang, **Xiaojun Chen** & Jinqiao Shi

**KeyWords:** *Federeated Learning*, *Differential Privacy*

**Abstract:** Federated learning can complete the neural network model training without uploading users’ private data. However, the deep leakage from gradients (DLG) and the compensatory reconstruction attack (CRA) can reconstruct the training data according to the gradients uploaded by users. We propose an efficient federated convolutional neural network scheme with differential privacy to solve this problem. By adding Gaussian noise to the fully connected layers of the convolutional neural network, the attacker cannot identify the critical gradients that cause privacy leakage. The cumulative privacy loss is tracked using the analytical moments accountant technique. We conduct extensive experiments on the MNIST and CIFAR10 datasets to evaluate our defense algorithm. After selecting appropriate parameters, the results show that our defense algorithm can defend against DLG and CRA while maintaining a high model accuracy.
