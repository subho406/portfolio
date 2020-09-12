---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'OmniNet: A unified architecture for multi-modal multi-task learning'
subtitle: ''
summary: ''
authors:
- Subhojeet Pramanik
- Priyanka Agrawal
- Aman Hussain
tags: []
categories: []
date: '2019-07-01'
lastmod: 2020-09-11T21:01:11+05:30
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2020-09-11T15:32:29.744624Z'
publication_types:
- 2
abstract: 'Transformer is a popularly used neural network architecture, especially for language understanding. We introduce an extended and unified architecture that can be used for tasks involving a variety of modalities like image, text, videos, etc. We propose a spatio-temporal cache mechanism that enables learning spatial dimension of the input in addition to the hidden states corresponding to the temporal input sequence. The proposed architecture further enables a single model to support tasks with multiple input modalities as well as asynchronous multi-task learning, thus we refer to it as OmniNet. For example, a single instance of OmniNet can concurrently learn to perform the tasks of part-of-speech tagging, image captioning, visual question answering and video activity recognition. We demonstrate that training these four tasks together results in about three times compressed model while retaining the performance in comparison to training them individually. We also show that using this neural network pre-trained on some modalities assists in learning unseen tasks such as video captioning and video question answering. This illustrates the generalization capacity of the self-attention mechanism on the spatio-temporal cache present in OmniNet.
'
publication: '*CoRR*'
url_pdf: http://arxiv.org/abs/1907.07804
url_code: https://github.com/subho406/OmniNet
---
