---
title: 'When Good and Reproducible Results are a Giant with Feet of Clay: The Importance
  of Software Quality in NLP'
authors:
- Sara Papi
- Marco Gaido
- Andrea Pilzer
- Matteo Negri
date: '2024-08-01'
publishDate: '2024-08-17T04:54:32.364331Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 62nd Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)*'
abstract: Despite its crucial role in research experiments, code correctness is often
  presumed solely based on the perceived quality of results. This assumption, however,
  comes with the risk of erroneous outcomes and, in turn, potentially misleading findings.
  To mitigate this risk, we posit that the current focus on reproducibility should
  go hand in hand with the emphasis on software quality. We support our arguments
  with a case study in which we identify and fix three bugs in widely used implementations
  of the state-of-the-art Conformer architecture. Through experiments on speech recognition
  and translation in various languages, we demonstrate that the presence of bugs does
  not prevent the achievement of good and reproducible results, which however can
  lead to incorrect conclusions that potentially misguide future research. As countermeasures,
  we release pangoliNN, a library dedicated to testing neural models, and propose
  a Code-quality Checklist, with the goal of promoting coding best practices and improving
  software quality within the NLP community.
links:
- name: ACL Anthology
  url: https://aclanthology.org/2024.acl-long.200
- GitHub (Pangolinn):
  url: https://github.com/hlt-mt/pangolinn
- GitHub (Case Study Code and Models):
  url: https://github.com/hlt-mt/FBK-fairseq/blob/master/fbk_works/BUGFREE_CONFORMER.md
- name: arXiv
  url: https://arxiv.org/abs/2303.16166
- name: Poster
  url: https://drive.google.com/file/d/18eh4Nmc94NBPAbml7goZzF1DtIe4pTGK/view?usp=sharing
- name: Slides
  url: https://drive.google.com/file/d/1A8B1JNwMoMSZSot1IrC_20GGPXeOteYx/view?usp=sharing
- name: Video
  url: https://youtu.be/EtMqFP1K2Ao
---
