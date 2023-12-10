---
title: 'Dealing with training and test segmentation mismatch: FBK@IWSLT2021'
authors:
- Sara Papi
- Marco Gaido
- Matteo Negri
- Marco Turchi
date: '2021-08-01'
publishDate: '2023-12-10T21:48:05.295412Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 18th International Conference on Spoken Language
  Translation (IWSLT 2021)*'
doi: 10.18653/v1/2021.iwslt-1.8
abstract: This paper describes FBK′s system submission to the IWSLT 2021 Offline Speech
  Translation task. We participated with a direct model, which is a Transformer-based
  architecture trained to translate English speech audio data into German texts. The
  training pipeline is characterized by knowledge distillation and a two-step fine-tuning
  procedure. Both knowledge distillation and the first fine-tuning step are carried
  out on manually segmented real and synthetic data, the latter being generated with
  an MT system trained on the available corpora. Differently, the second fine-tuning
  step is carried out on a random segmentation of the MuST-C v2 En-De dataset. Its
  main goal is to reduce the performance drops occurring when a speech translation
  model trained on manually segmented data (i.e. an ideal, sentence-like segmentation)
  is evaluated on automatically segmented audio (i.e. actual, more realistic testing
  conditions). For the same purpose, a custom hybrid segmentation procedure that accounts
  for both audio content (pauses) and for the length of the produced segments is applied
  to the test data before passing them to the system. At inference time, we compared
  this procedure with a baseline segmentation method based on Voice Activity Detection
  (VAD). Our results indicate the effectiveness of the proposed hybrid approach, shown
  by a reduction of the gap with manual segmentation from 8.3 to 1.4 BLEU points.
links:
- name: URL
  url: https://aclanthology.org/2021.iwslt-1.8
---
