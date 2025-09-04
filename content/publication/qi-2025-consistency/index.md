---
title: On the Consistency of Multilingual Context Utilization in Retrieval-Augmented
  Generation
authors:
- Jirui Qi
- Raquel Fernández
- Arianna Bisazza
date: '2025-04-01'
publishDate: '2025-09-04T14:56:25.504161Z'
publication_types:
- article-journal
publication: '*arXiv preprint arXiv:2504.00597*'
abstract: Retrieval-augmented generation (RAG) with large language models (LLMs) has
  demonstrated strong performance in multilingual question-answering (QA) tasks by
  leveraging relevant passages retrieved from corpora. In multilingual RAG (mRAG),
  the retrieved passages can be written in languages other than that of the query
  entered by the user, making it challenging for LLMs to effectively utilize the provided
  information. Recent research suggests that retrieving passages from multilingual
  corpora can improve RAG performance, particularly for low-resource languages. However,
  the extent to which LLMs can leverage different kinds of multilingual contexts to
  generate accurate answers, *independently from retrieval quality*, remains understudied.
  In this paper, we conduct an extensive assessment of LLMs' ability to (i) make consistent
  use of a relevant passage regardless of its language, (ii) respond in the expected
  language, and (iii) focus on the relevant passage even when multiple `distracting'
  passages in different languages are provided in the context. Our experiments with
  four LLMs across three QA datasets covering a total of 48 languages reveal a surprising
  ability of LLMs to extract the relevant information from out-language passages,
  but a much weaker ability to formulate a full answer in the correct language. Our
  analysis, based on both accuracy and feature attribution techniques, further shows
  that distracting passages negatively impact answer quality regardless of their language.
  However, distractors in the query language exert a slightly stronger influence.
  Taken together, our findings deepen the understanding of how LLMs utilize context
  in mRAG systems, providing directions for future improvements.
links:
- name: URL
  url: https://arxiv.org/abs/2504.00597
---
