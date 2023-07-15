---
title: "Boundary-Driven Table-Filling for Aspect Sentiment Triplet Extraction"
collection: publications
permalink: /publication/EMNLP2022_BDTF
excerpt: 'Yice Zhang, **Yifan Yang**(co-first author), Yihui Li, Bin Liang, Shiwei Chen, Yixue Dang, Min Yang, Ruifeng Xu'
date: 2022-12-07
venue: 'EMNLP'
paperurl: 'https://aclanthology.org/2022.emnlp-main.435/'
citation: 'Yice Zhang, Yifan Yang, Yihui Li, Bin Liang, Shiwei Chen, Yixue Dang, Min Yang, and Ruifeng Xu. 2022. Boundary-Driven Table-Filling for Aspect Sentiment Triplet Extraction. In Proceedings of the 2022 Conference on Empirical Methods in Natural Language Processing, pages 6485–6498, Abu Dhabi, United Arab Emirates. Association for Computational Linguistics.'
---
Aspect Sentiment Triplet Extraction (ASTE) aims to extract the aspect terms along with the corresponding opinion terms and the expressed sentiments in the review, which is an important task in sentiment analysis. Previous research efforts generally address the ASTE task in an end-to-end fashion through the table-filling formalization, in which the triplets are represented by a two-dimensional (2D) table of word-pair relations. Under this formalization, a term-level relation is decomposed into multiple independent word-level relations, which leads to relation inconsistency and boundary insensitivity in the face of multi-word aspect terms and opinion terms. To overcome these issues, we propose Boundary-Driven Table-Filling (BDTF), which represents each triplet as a relation region in the 2D table and transforms the ASTE task into detection and classification of relation regions. We also notice that the quality of the table representation greatly affects the performance of BDTF. Therefore, we develop an effective relation representation learning approach to learn the table representation, which can fully exploit both word-to-word interactions and relation-to-relation interactions. Experiments on several public benchmarks show that the proposed approach achieves state-of-the-art performances.
