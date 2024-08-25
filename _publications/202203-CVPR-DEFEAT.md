---
title: "DEFEAT: Deep Hidden Feature Backdoor Attacks by Imperceptible Perturbation and Latent Representation Constraints"
collection: publications
category: pubpapers
permalink: /publication/202203-CVPR-DEFEAT
date: 2022-03-03
venue: 'Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition(CVPR)'
paperurl: 'https://openaccess.thecvf.com/content/CVPR2022/html/Zhao_DEFEAT_Deep_Hidden_Feature_Backdoor_Attacks_by_Imperceptible_Perturbation_and_CVPR_2022_paper.html'
---
**Authors:** Zhendong Zhao, **Xiaojun Chen**, Yuexin Xuan, Ye Dong, Dakui Wang, Kaitai Liang

**KeyWords:** *Graph Federated Learning*, *Backdoor Attacks*

**Abstract:** Backdoor attack is a type of serious security threat to deep learning models. An adversary can provide users with a model trained on poisoned data to manipulate prediction behavior in test stage using a backdoor. The backdoored models behave normally on clean images, yet can be activated and output incorrect prediction if the input is stamped with a specific trigger pattern. Most existing backdoor attacks focus on manually defining imperceptible triggers in input space without considering the abnormality of triggers' latent representations in the poisoned model. These attacks are susceptible to backdoor detection algorithms and even visual inspection. In this paper, We propose a novel and stealthy backdoor attack-DEFEAT. It poisons the clean data using adaptive imperceptible perturbation and restricts latent representation during training process to strengthen our attack's stealthiness and resistance to defense algorithms. We conduct extensive experiments on multiple image classifiers using real-world datasets to demonstrate that our attack can 1) hold against the state-of-the-art defenses, 2) deceive the victim model with high attack success without jeopardizing model utility, and 3) provide practical stealthiness on image data.
