---
title: 'Dodging the Data Bottleneck: Automatic Subtitling with Automatically Segmented
  ST Corpora'
authors:
- Sara Papi
- Alina Karakanta
- Matteo Negri
- Marco Turchi
date: '2022-11-01'
publishDate: '2023-12-12T20:35:55.075626Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 2nd Conference of the Asia-Pacific Chapter of the
  Association for Computational Linguistics and the 12th International Joint Conference
  on Natural Language Processing (Volume 2: Short Papers)*'
abstract: Speech translation for subtitling (SubST) is the task of automatically translating
  speech data into well-formed subtitles by inserting subtitle breaks compliant to
  specific displaying guidelines. Similar to speech translation (ST), model training
  requires parallel data comprising audio inputs paired with their textual translations.
  In SubST, however, the text has to be also annotated with subtitle breaks. So far,
  this requirement has represented a bottleneck for system development, as confirmed
  by the dearth of publicly available SubST corpora. To fill this gap, we propose
  a method to convert existing ST corpora into SubST resources without human intervention.
  We build a segmenter model that automatically segments texts into proper subtitles
  by exploiting audio and text in a multimodal fashion, achieving high segmentation
  quality in zero-shot conditions. Comparative experiments with SubST systems respectively
  trained on manual and automatic segmentations result in similar performance, showing
  the effectiveness of our approach.
links:
- name: URL
  url: https://aclanthology.org/2022.aacl-short.59
---
