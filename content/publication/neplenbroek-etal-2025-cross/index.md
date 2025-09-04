---
title: 'Cross-Lingual Transfer of Debiasing and Detoxification in Multilingual LLMs:
  An Extensive Investigation'
authors:
- Vera Neplenbroek
- Arianna Bisazza
- Raquel Fernández
date: '2025-07-01'
publishDate: '2025-09-04T12:19:02.229648Z'
publication_types:
- paper-conference
publication: '*Findings of the Association for Computational Linguistics: ACL 2025*'
doi: 10.18653/v1/2025.findings-acl.145
abstract: Recent generative large language models (LLMs) show remarkable performance
  in non-English languages, but when prompted in those languages they tend to express
  higher harmful social biases and toxicity levels. Prior work has shown that finetuning
  on specialized datasets can mitigate this behavior, and doing so in English can
  transfer to other languages. In this work, we investigate the impact of different
  finetuning methods on the model′s bias and toxicity, but also on its ability to
  produce fluent and diverse text. We reduce biases by finetuning on curated non-harmful
  text, but find only direct preference optimization to be effective for mitigating
  toxicity. The mitigation caused by applying these methods in English also transfers
  to non-English languages. We find evidence that the extent to which transfer takes
  place can be predicted by the amount of data in a given language present in the
  model′s pretraining data. However, this transfer of bias and toxicity mitigation
  often comes at the expense of decreased language generation ability in non-English
  languages, highlighting the importance of developing language-specific bias and
  toxicity mitigation methods.
links:
- name: URL
  url: https://aclanthology.org/2025.findings-acl.145/
---
