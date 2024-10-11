---
# title: Identifiability Results for Multimodal Contrastive Learning
# authors:
# - Imant Daunhawer
# - Alice Bizeul
# - Emanuele Palumbo
# - Alexander Marx
# - Julia E. Vogt
# date: '2023-01-01'
# publishDate: '2024-10-09T13:59:37.591048Z'
# publication_types:
# - paper-conference
# publication: '*International Conference on Learning Representations*'
# url_pdf: https://openreview.net/pdf?id=U_2kuqoTcB
title: Identifiability Results for Multimodal Contrastive Learning
authors:
- Imant Daunhawer
- Alice Bizeul
- Emanuele Palumbo
- Alexander Marx
- Julia E. Vogt
date: '2023-01-16'
publishDate: '2024-10-09T13:59:37.591048Z'
subtitle: 'Poster @ ICLR 2023'

tags: []
categories: []
featured: false
draft: false
publication_short: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: 'Center'
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publication_types:
- '1'
abstract: "
Contrastive learning is a cornerstone underlying recent progress in multi-view and multimodal learning, e.g., in representation learning with image/caption pairs. While its effectiveness is not yet fully understood, a line of recent work reveals that contrastive learning can invert the data generating process and recover ground truth latent factors shared between views. In this work, we present new identifiability results for multimodal contrastive learning, showing that it is possible to recover shared factors in a more general setup than the multi-view setting studied previously. Specifically, we distinguish between the multi-view setting with one generative mechanism (e.g., multiple cameras of the same type) and the multimodal setting that is characterized by distinct mechanisms (e.g., cameras and microphones). Our work generalizes previous identifiability results by redefining the generative process in terms of distinct mechanisms with modality-specific latent variables. We prove that contrastive learning can block-identify latent factors shared between modalities, even when there are nontrivial dependencies between factors. We empirically verify our identifiability results with numerical simulations and corroborate our findings on a complex multimodal dataset of image/text pairs. Zooming out, our work provides a theoretical basis for multimodal representation learning and explains in which settings multimodal contrastive learning can be effective in practice."
publication: 'ICLR 2023'
links:
- name: URL
  url :https://openreview.net/pdf?id=U_2kuqoTcB
---
---
