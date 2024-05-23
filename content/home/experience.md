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
  - title: Applied Research Scientist
    company: Ericsson
    company_url: ''
    company_logo: ericsson-logo
    location: Los Angeles
    date_start: '2023-02-20'
    date_end: ''
    description: |2-
        Interpretable Video Translation by generative AI:

        * Created the largest dataset of talking head videos from YouTube. 
        * Established multi-person & lingual audio/video synchronization.
        * Refined the facial landmark generation network for better articulation. 
        * Used diffusion to achieve immersive lip synchronization in videos with translated audio.

  - title: Research Intern
    company: Meta
    company_url: ''
    company_logo: meta-logo
    location: Bethesda, Maryland
    date_start: '2022-06-04'
    date_end: '2022-08-26'
    description: |2-
        2D-3D style transfer for VR

        * Achieved real-time inference
        * Human interaction for personalized customization.
        * Preserved 3D visual reality.
        * Utilized PyTorch3D \& nvdiffrast as differential rendering.
        * Preserved object style consistency by semantic style transfer.

  - title: Applied Research Intern
    company: PingAn
    company_url: ''
    company_logo: pingan
    location: Bethesda, Meryland
    date_start: '2019-05-01'
    date_end: '2019-12-31'
    description: |2-
        Symmetric learning for Fracture Detection in Pelvic Trauma X-ray:

        * Deployed in Chang Gung Memorial Hospital in Taiwan. 
        * Paper accepted by ECCV 2020 with poster.
        * Mimicked radiologists to detect fractures by comparing bilateral symmetric regions.
        * Focused on anatomical asymmetry with contrastive learning.

  - title: Applied Research Intern
    company: NVIDIA
    company_url: ''
    company_logo: Nvidia_logo
    location: Bethesda, Meryland
    date_start: '2018-05-01'
    date_end: '2018-12-31'
    description: |2-
        Deep Hierarchical Multi-label Classification of Chest X-ray:
    
        * Paper accepted by MIDL 2019 with oral presentation.
        * Paper accepted by Journal ``Medical Image Analysis".
        * Mimicked radiologists to classify abnormality with clinical taxonomy.
        * Improved classification AUC from 0.87 to 0.89.
        * Robust to incompletely labeled data and preserved $85\%$ performance drop.

  - title: Applied Research Intern
    company: PingAn
    company_url: ''
    company_logo: pingan
    location: Shanghai
    date_start: '2017-05-01'
    date_end: '2017-08-31'
    description: |2-
        Lung nodule detection in CT images:

        * Achieved rank 6/2887 teams in the Skylake competition by Intel and Alibaba.
        * Applied PyTorch, 3D UNet and Caffe, Faster RCNN to detect lung nodules in 1000 CT scans.
        * Used fusion method to achieve false positive reduction.

design:
  columns: '2'
---
