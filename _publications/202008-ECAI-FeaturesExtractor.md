---
title: "A Shared-Word Sensitive Sequence-to-Sequence Features Extractor for Sentences Matching"
collection: publications
category: conferences
permalink: /publication/202008-ECAI-FeaturesExtractor
date: 2020-08-29
venue: 'The 24th European Conference on Artificial Intelligence(ECAI)'
paperurl: 'https://ebooks.iospress.nl/pdf/doi/10.3233/FAIA200329'
---
**Authors:** Jinqing Li, Dakui Wang, **Xiaojun Chen**, Pencheng Liao, Shujuan Chen

**KeyWords:** *Nature Language Processing*, *Sequence2sequence model*

**Abstract:** Sentences matching is a basic task in Natural Language Processing (NLP). Interaction-based methods, which employ interactions between words of two sentences and construct word-level matching features to classify, are generally used due to their fine-grained features. However, they have many invalid interactions that may affect matching precision. In this paper, we limit the objects of interacting to shared words4 of two sentences. On the one hand, they can reduce invalid interactions. On the other hand, because of the different context semantics, the representation of the same word may be quite different, conversely, the representation difference can also be used to reflect the semantic difference of different contexts. To better extract global features of shared words, we introduce a sequence-to-sequence features extractor to force decoder to learn more contextual information from encoder. We implement the method based on Transformer[28], with syntactic parsing as additional knowledge. Our proposed method achieved better performance than strong baselines and the experiment results also demonstrate the efficiency of sequence-to-sequence features extractor and significance of the shared words.
