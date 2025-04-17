---
title: Cross-Lingual Consistency of Factual Knowledge in Multilingual Language Models
authors:
- Jirui Qi
- Raquel Fernández
- Arianna Bisazza
date: '2023-12-01'
publishDate: '2025-04-17T16:56:51.635142Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 2023 Conference on Empirical Methods in Natural
  Language Processing*'
doi: 10.18653/v1/2023.emnlp-main.658
abstract: Multilingual large-scale Pretrained Language Models (PLMs) have been shown
  to store considerable amounts of factual knowledge, but large variations are observed
  across languages. With the ultimate goal of ensuring that users with different language
  backgrounds obtain consistent feedback from the same model, we study the cross-lingual
  consistency (CLC) of factual knowledge in various multilingual PLMs. To this end,
  we propose a Ranking-based Consistency (RankC) metric to evaluate knowledge consistency
  across languages independently from accuracy. Using this metric, we conduct an in-depth
  analysis of the determining factors for CLC, both at model level and at language-pair
  level. Among other results, we find that increasing model size leads to higher factual
  probing accuracy in most languages, but does not improve cross-lingual consistency.
  Finally, we conduct a case study on CLC when new factual associations are inserted
  in the PLMs via model editing. Results on a small sample of facts inserted in English
  reveal a clear pattern whereby the new piece of knowledge transfers only to languages
  with which English has a high RankC score. All code and data are released at https://github.com/Betswish/Cross-Lingual-Consistency.
links:
- name: URL
  url: https://aclanthology.org/2023.emnlp-main.658/
---
