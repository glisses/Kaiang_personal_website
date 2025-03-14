---
title: '[Research Paper] MambaReg: Mamba-Based Disentangled Convolutional Sparse Coding for Unsupervised
  Deformable Multi-Modal Image Registration'

summary: 'Kaiang Wen, Bin Xie, Bin Duan, Yan Yan. arXiv preprint arXiv:2411.01399.' 

# Is this a featured talk? (true/false)
featured: false

authors:
- Kaiang Wen
- Bin Xie
- Bin Duan
- Yan Yan

date: '2024-11-03'
# Schedule page publish date (NOT talk date).
publishDate: '2024-11-03T00:00:00Z'

publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.2411.01399
abstract: Precise alignment of multi-modal images with inherent feature discrepancies
  poses a pivotal challenge in deformable image registration. Traditional learning-based
  approaches often consider registration networks as black boxes without interpretability.
  One core insight is that disentangling alignment features and non-alignment features
  across modalities bring benefits. Meanwhile, it is challenging for the prominent
  methods for image registration tasks, such as convolutional neural networks, to
  capture long-range dependencies by their local receptive fields. The methods often
  fail when the given image pair has a large misalignment due to the lack of effectively
  learning long-range dependencies and correspondence. In this paper, we propose MambaReg,
  a novel Mamba-based architecture that integrates Mamba's strong capability in capturing
  long sequences to address these challenges. With our proposed several sub-modules,
  MambaReg can effectively disentangle modality-independent features responsible for
  registration from modality-dependent, non-aligning features. By selectively attending
  to the relevant features, our network adeptly captures the correlation between multi-modal
  images, enabling focused deformation field prediction and precise image alignment.
  The Mamba-based architecture seamlessly integrates the local feature extraction
  power of convolutional layers with the long-range dependency modeling capabilities
  of Mamba. Experiments on public non-rigid RGB-IR image datasets demonstrate the
  superiority of our method, outperforming existing approaches in terms of registration
  accuracy and deformation field smoothness.

tags:
- Computer Science - Computer Vision and Pattern Recognition

links:
- name: URL
  url: http://arxiv.org/abs/2411.01399

image:
  caption: 'deformable registration'
  focal_point: Right

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
# url_code: 'https://github.com'
# url_pdf: ''
# url_slides: 'https://slideshare.net'
# url_video: 'https://youtube.com'

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
research_projects:
  - MambaReg
---
