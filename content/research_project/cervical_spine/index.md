---
title: 'Knowledge-Guided Gated Multitasking Network for Cervical Spine Degeneration Evaluation'

summary: 'Conducted research on cervical spondylosis measurement using a U-Net-based model for segmentation and MMPose for pose estimation, achieving a 75% reduction in Cobb metric error.' 

# Is this a featured talk? (true/false)
featured: false

authors:
- admin

date: '2023-01-30'
# Schedule page publish date (NOT talk date).
publishDate: '2024-11-03T00:00:00Z'


abstract: Cervical spondylosis is one of the most common degenerative diseases occurring in any population, which seriously affects the health and quality of our lives. Compared to diseases with explicit lesions, such as cancer, hydroncus, or fracture, the degeneration of the cervical spine cannot be explicitly detected from the appearance of medical images, which are usually diagnosed with the combination of appearance and professional metric measurement in clinical practice. However, such measurements are in general complex, tedious, and time-consuming to be obtained. Traditional deep learning methods, such as segmentation-based methods, may be capable of detecting cervical spondylosis, however, those methods require an enormous amount of manual annotation and lack attention to salient information such as edges and corner points, which makes it difficult to meet practical needs and precision. To address the above problems, a novel Gated Multi-Tasking Keypoint Detection framework is proposed to detect the cervical spondylosis by measuring multiple degenerative metrics in a multi-task learning manner. The gated keypoint selection mechanism of the model is adjustable for different measurement needs of the clinic. By sharing model parameters for keypoint detection and metric calculation through the multi-task learning manner in an end-to-end architecture, richer target information can be learned using lightweight annotations. In addition, the introduction of an anatomical structure knowledge-guided adaptation module makes it a better predictor without adding annotations. Experiments on our medical image dataset demonstrate the superiority of the proposed approach and prove its potential for application in clinical diagnosis.

tags:
- Computer Science - Computer Vision and Medical Imaging

links:
- name: URL
  url: https://vipl.ict.ac.cn/edu/paststudent/visited/202211/t20221118_123592.html

image:
  caption: 'Cervical Spine Degeneration'
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
  - cervical_spine
---
