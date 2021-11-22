---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Applied Research Intern
    company: PingAn
    company_url: ''
    company_logo: org-gc
    location: Bethesda
    date_start: '2019-05-01'
    date_end: '2019-12-31'
    description: |2-
        Symmetric learning for Fracture Detection in Pelvic Trauma X-ray:

        * Accepted by ECCV with poster.
        * Achieved 98.8% AUC for all fractures, with is 0.8% higher than baseline model.
        * Created alignment between original/flipped images according to pelvic structure landmark detection.
        * Constructed Siamese network with fusion layer to incorporate symmetric information.
        * Aligned Siamese features instead of input images to reduce distortion artifacts.
        * Applied pixel-wise contrastive loss to learn pathologically asymmetric information explicitly.

  - title: Applied Research Intern
    company: NVIDIA
    company_url: ''
    company_logo: org-x
    location: Bethesda
    date_start: '2018-05-01'
    date_end: '2018-12-31'
    description: |2-
        Deep Hierarchical Multi-label Classification of Chest X-ray:
    
        * Accepted by MIDL 2019 with oral and special invitation to Journal Medical Image Analysis.
        * Achieved 89% AUC of all diseases on PLCO dataset, which is the state of the art.
        * Constructed Hierarchical label structure following clinical taxonomy.
        * Trained with conditional probabilities first and then fine-tuned with full probabilities training.
        * Derived a numerically stable formulation to calculate the cross entropy loss using full probabilities.
        * Introduced conditional AUCs for hierarchical-label performance evaluation.

 - title: Applied Research Intern
    company: PingAn
    company_url: ''
    company_logo:
    location: Shanghai
    date_start: '2017-05-01'
    date_end: '2017-8-31'
    description: |2-
        Lung nodule detection in CT images:

        * Achieved rank 6 out of 2887 teams in the Skylake competition sponsored by Intel and Alibaba.
        * Applied PyTorch, 3D UNet and Caffe, Faster RCNN to detect lung nodules in 1000 CT scans.
        * Truncated the last two deconvolution layers in U Net changed the output as RPN structure and added new output branches before every deconvolution layer. 
        * Used fusion method to achieve false positive reduction.

design:
  columns: '2'
---
