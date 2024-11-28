---
title: "A Reproducibility Study of Goldilocks: Just-Right Tuning of BERT for TAR"
collection: publications
permalink: /publication/2024-03-15-goldilocks-reproduce
excerpt: 
date: 2024-03-15
venue: 'Proceedings of the 46th European Conference on Information Retrieval (ECIR)'
slidesurl: 
paperurl: 'https://arxiv.org/pdf/2401.08104'
citation: 'Xinyu Mao, Bevan Koopman and Guido Zuccon. 2024. A Reproducibility Study of Goldilocks: Just-Right Tuning of BERT for TAR. In Proceedings of the 46th European Conference on Information Retrieval (ECIR 2024).'
---
## Abstract
Screening documents is a tedious and time-consuming aspect of high-recall retrieval tasks, such as compiling a systematic literature review, where the goal is to identify all relevant documents for a topic. To help streamline this process, many Technology-Assisted Review (TAR) methods leverage active learning techniques to reduce the number of documents requiring review. BERT-based models have shown high effectiveness in text classification, leading to interest in their potential use in TAR workflows. In this paper, we investigate recent work that examined the impact of further pre-training epochs on the effectiveness and efficiency of a BERT-based active learning pipeline. We first report that we could replicate the original experiments on two specific TAR datasets, confirming some of the findings: importantly, that further pre-training is critical to high effectiveness, but requires attention in terms of selecting the correct training epoch. We then investigate the generalisability of the pipeline on a different TAR task, that of medical systematic reviews. In this context, we show that there is no need for further pre-training if a domain-specific BERT backbone is used within the active learning pipeline. This finding provides practical implications for using the studied active learning pipeline within domain-specific TAR tasks.