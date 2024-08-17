---
title: 'StreamAtt: Direct Streaming Speech-to-Text Translation with Attention-based
  Audio History Selection'
authors:
- Sara Papi
- Marco Gaido
- Matteo Negri
- Luisa Bentivogli
date: '2024-08-01'
publishDate: '2024-08-17T04:54:32.353587Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 62nd Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)*'
abstract: Streaming speech-to-text translation (StreamST) is the task of automatically
  translating speech while incrementally receiving an audio stream. Unlike simultaneous
  ST (SimulST), which deals with pre-segmented speech, StreamST faces the challenges
  of handling continuous and unbounded audio streams. This requires additional decisions
  about what to retain of the previous history, which is impractical to keep entirely
  due to latency and computational constraints. Despite the real-world demand for
  real-time ST, research on streaming translation remains limited, with existing works
  solely focusing on SimulST. To fill this gap, we introduce StreamAtt, the first
  StreamST policy, and propose StreamLAAL, the first StreamST latency metric designed
  to be comparable with existing metrics for SimulST. Extensive experiments across
  all 8 languages of MuST-C v1.0 show the effectiveness of StreamAtt compared to a
  naive streaming baseline and the related state-of-the-art SimulST policy, providing
  a first step in StreamST research.
links:
- name: ACL Anthology
  url: https://aclanthology.org/2024.acl-long.202
- name: GitHub
  url: https://github.com/hlt-mt/FBK-fairseq/blob/master/fbk_works/STREAMATT_STREAMLAAL.md
- name: arXiv
  url: https://arxiv.org/abs/2406.06097
- name: Poster
  url: https://drive.google.com/file/d/1hG1qNLyrpGPHxIpDKx3xihnIqcOelpzU/view?usp=sharing
- name: Slides
  url: https://drive.google.com/file/d/1YFN-kR_uH3nufzWxdXmkJQ8cI6N8lSUR/view?usp=sharing
- name: Video
  url: https://youtu.be/RDid_d6f3ZQ
---
