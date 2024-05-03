---
title: 'Speechformer: Reducing Information Loss in Direct Speech Translation'
authors:
- Sara Papi
- Marco Gaido
- Matteo Negri
- Marco Turchi
date: '2021-11-01'
publishDate: '2023-12-10T21:48:05.272112Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 2021 Conference on Empirical Methods in Natural
  Language Processing*'
doi: 10.18653/v1/2021.emnlp-main.127
abstract: Transformer-based models have gained increasing popularity achieving state-of-the-art
  performance in many research fields including speech translation. However, Transformer′s
  quadratic complexity with respect to the input sequence length prevents its adoption
  as is with audio signals, which are typically represented by long sequences. Current
  solutions resort to an initial sub-optimal compression based on a fixed sampling
  of raw audio features. Therefore, potentially useful linguistic information is not
  accessible to higher-level layers in the architecture. To solve this issue, we propose
  Speechformer, an architecture that, thanks to reduced memory usage in the attention
  layers, avoids the initial lossy compression and aggregates information only at
  a higher level according to more informed linguistic criteria. Experiments on three
  language pairs (en→de/es/nl) show the efficacy of our solution, with gains of up
  to 0.8 BLEU on the standard MuST-C corpus and of up to 4.0 BLEU in a low resource
  scenario.
links:
- name: URL
  url: https://aclanthology.org/2021.emnlp-main.127
- name: Poster
  url: https://docs.google.com/presentation/d/1NNtpbsswe1-KR4sgnlrVYZcKLJ95RHdSlSoBwGkCn10/edit?usp=sharing
- name: Slides
  url: https://docs.google.com/presentation/d/1wpXg7_2gUQrvWmly_MAvsTf_AbuJeAmJIhlHXOHl6zM/edit?usp=sharing
- name: Video
  url: https://underline.io/lecture/37646-speechformer-reducing-information-loss-in-direct-speech-translation
---
