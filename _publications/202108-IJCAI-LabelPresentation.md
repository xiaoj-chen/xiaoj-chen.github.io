---
title: "Enhancing Label Representations with Relational Inductive Bias Constraint for Fine-Grained Entity Typing"
collection: publications
category: pubpapers
permalink: /publication/202108-IJCAI-LabelPresentation
date: 2021-08-01
venue: 'International Joint Conference on Artificial Intelligence(IJCAI)'
paperurl: 'https://www.ijcai.org/proceedings/2021/0529.pdf'
---
**Authors:** Jinqing Li, **Xiaojun Chen**, Dakui Wang, Yuwei Li

**KeyWords:** *Graph Nerual Network*

**Abstract:** Fine-Grained Entity Typing (FGET) is a task that aims at classifying an entity mention into a wide range of entity label types. Recent researches improve the task performance by imposing the labelrelational inductive bias based on the hierarchy of labels or label co-occurrence graph. However, they usually overlook explicit interactions between instances and labels which may limit the capability of label representations. Therefore, we propose a novel method based on a two-phase graph network for the FGET task to enhance the label representations, via imposing the relational inductive biases of instance-to-label and label-to-label. In the phase I, instance features will be introduced into label representations to make the label representations more representative. In the phase II, interactions of labels will capture dependency relationships among them thus make label representations more smooth. During prediction, we introduce a pseudo-label generator for the construction of the two-phase graph. The input instances differ from batch to batch so that the label representations are dynamic. Experiments on three public datasets verify the effectiveness and stability of our proposed method and achieve stateof-the-art results on their testing sets.
