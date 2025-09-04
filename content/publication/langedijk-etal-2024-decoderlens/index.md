---
title: 'DecoderLens: Layerwise Interpretation of Encoder-Decoder Transformers'
authors:
- Anna Langedijk
- Hosein Mohebbi
- Gabriele Sarti
- Willem Zuidema
- Jaap Jumelet
date: '2024-06-01'
publishDate: '2025-09-04T12:09:45.839504Z'
publication_types:
- paper-conference
publication: '*Findings of the Association for Computational Linguistics: NAACL 2024*'
abstract: In recent years, several interpretability methods have been proposed to
  interpret the inner workings of Transformer models at different levels of precision
  and complexity.In this work, we propose a simple but effective technique to analyze
  encoder-decoder Transformers. Our method, which we name DecoderLens, allows the
  decoder to cross-attend representations of intermediate encoder activations instead
  of using the default final encoder output.The method thus maps uninterpretable intermediate
  vector representations to human-interpretable sequences of words or symbols, shedding
  new light on the information flow in this popular but understudied class of models.We
  apply DecoderLens to question answering, logical reasoning, speech recognition and
  machine translation models, finding that simpler subtasks are solved with high precision
  by low and intermediate encoder layers.
links:
- name: URL
  url: https://aclanthology.org/2024.findings-naacl.296
---
