---
title: Model Internals-based Answer Attribution for Trustworthy Retrieval-Augmented
  Generation
authors:
- Jirui Qi
- Gabriele Sarti
- Raquel Fernández
- Arianna Bisazza
date: '2024-11-01'
publishDate: '2025-09-04T10:23:10.922927Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 2024 Conference on Empirical Methods in Natural
  Language Processing*'
doi: 10.18653/v1/2024.emnlp-main.347
abstract: Ensuring the verifiability of model answers is a fundamental challenge for
  retrieval-augmented generation (RAG) in the question answering (QA) domain. Recently,
  self-citation prompting was proposed to make large language models (LLMs) generate
  citations to supporting documents along with their answers. However, self-citing
  LLMs often struggle to match the required format, refer to non-existent sources,
  and fail to faithfully reflect LLMs' context usage throughout the generation. In
  this work, we present MIRAGE -- Model Internals-based RAG Explanations -- a plug-and-play
  approach using model internals for faithful answer attribution in RAG applications.
  MIRAGE detects context-sensitive answer tokens and pairs them with retrieved documents
  contributing to their prediction via saliency methods. We evaluate our proposed
  approach on a multilingual extractive QA dataset, finding high agreement with human
  answer attribution. On open-ended QA, MIRAGE achieves citation quality and efficiency
  comparable to self-citation while also allowing for a finer-grained control of attribution
  parameters. Our qualitative evaluation highlights the faithfulness of MIRAGE`s attributions
  and underscores the promising application of model internals for RAG answer attribution.
  Code and data released at https://github.com/Betswish/MIRAGE.
links:
- name: URL
  url: https://aclanthology.org/2024.emnlp-main.347/
---
