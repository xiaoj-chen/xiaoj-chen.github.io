---
title: "Practical and General Backdoor Attacks against Vertical Federated Learning"
collection: publications
category: pubpapers
permalink: /publication/202306-ECML-PKDD-BAVFL
date: 2023-06-19
venue: 'Joint European Conference on Machine Learning and Knowledge Discovery in Databases(ECML PKDD)'
paperurl: 'https://arxiv.org/abs/2306.10746'
---
**Authors:** Yuexin Xuan, **Xiaojun Chen**, Zhendong Zhao, Bisheng Tang, Ye Dong

**KeyWords:** *Vertical Federated Learning*, *Backdoor Attacks*

**Abstract:** Federated learning (FL), which aims to facilitate data collaboration across multiple organizations without exposing data privacy, encounters potential security risks. One serious threat is backdoor attacks, where an attacker injects a specific trigger into the training dataset to manipulate the model's prediction. Most existing FL backdoor attacks are based on horizontal federated learning (HFL), where the data owned by different parties have the same features. However, compared to HFL, backdoor attacks on vertical federated learning (VFL), where each party only holds a disjoint subset of features and the labels are only owned by one party, are rarely studied. The main challenge of this attack is to allow an attacker without access to the data labels, to perform an effective attack. To this end, we propose BadVFL, a novel and practical approach to inject backdoor triggers into victim models without label information. BadVFL mainly consists of two key steps. First, to address the challenge of attackers having no knowledge of labels, we introduce a SDD module that can trace data categories based on gradients. Second, we propose a SDP module that can improve the attack's effectiveness by enhancing the decision dependency between the trigger and attack target. Extensive experiments show that BadVFL supports diverse datasets and models, and achieves over 93% attack success rate with only 1% poisoning rate.
