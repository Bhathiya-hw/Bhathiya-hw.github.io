---
title: "A Simple Language Model for Multimodal Task-Oriented Dialogue with Symbolic Scene Representation"
authors:
  - me
  - P. Bartie
  - C. Dondrup
  - O. Lemon
date: "2023-01-01T00:00:00Z"
publishDate: "2023-01-01T00:00:00Z"
publication_types: ["paper-conference"]
publication: "Proceedings of the 15th International Conference on Computational Semantics"
publication_short: "IWCS 2023"
summary: "Conference paper generated from cite.bib."
tags:
  - Dialogue
  - Multimodal
  - Language Modeling
featured: false

abstract: 'SimpleMTOD is a simple language model which recasts several sub-tasks in multimodal task-oriented dialogues as sequence prediction tasks. SimpleMTOD is built on a large-scale transformer-based auto-regressive architecture, which has already proven to be successful in uni-modal task-oriented dialogues, and effectively leverages transfer learning from pretrained GPT-2. In-order to capture the semantics of visual scenes, we introduce both local and de-localized tokens for objects within a scene. De-localized tokens represent the type of an object rather than the specific object itself and so possess a consistent meaning across the dataset. SimpleMTOD achieves a state-of-the-art BLEU score (0.327) in the Response Generation sub-task of the SIMMC 2.0 test-std dataset while performing on par in other multimodal sub-tasks: Disambiguation, Coreference Resolution, and Dialog State Tracking. This is despite taking a minimalist approach for extracting visual (and non-visual) informa- tion. In addition the model does not rely on task-specific architectural changes such as classification heads.'

links:
  # - type: pdf
  - url: 'https://aclanthology.org/2023.iwcs-1.31.pdf'
url_code: 'https://github.com/Bhathiya-hw/simmc2'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---