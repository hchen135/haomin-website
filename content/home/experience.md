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
        Interpretable Video Translation:

        * I created the largest dataset of speaking face videos from a wild source - YouTube. 
        *I established an algorithm for synchronization between translated audio and original video at the sentence level in a multiperson and multilingual situation. 
        *I refined the facial landmark generation network for better articulation. 
        *I used the diffusion technique to achieve immersive lip synchronization in videos with translated audio.
        *In an internal user study, my video-audio synchronization proved to be more robust and generalizable compared to a similar product from ElevenLabs.

  - title: Research Intern
    company: Meta
    company_url: ''
    company_logo: meta-logo
    location: Bethesda, Maryland
    date_start: '2022-06-04'
    date_end: '2022-08-26'
    description: |2-
        3D scene style transfer with 2D style image by differential rendering:

        * Internship performance exceeds mentor/peers' expectation in review.
        * Learned style transfer, 3D mesh and rendering from scratch in one week.
        * Utilized PyTorch3D \& nvdiffrast as differential rendering to generate 2D views.
        * Optimized texture maps by style transfer between 2D rendered images and style image.
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

        * Paper accepted by ECCV 2020 with poster presentation.
        * Mimicked radiologists' practice by comparing vertical asymmetric areas via Siamese network.
        * Aligned Siamese features according to GNN-detected pelvic structure landmarks.
        * Learned anatomical asymmetry explicitly by novel pixel-wise contrastive loss.

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
        * Special invitation to Journal ``Medical Image Analysis" and paper accepted.
        * Followed clinical taxonomy to construct hierarchical multi-label classification.
        * Developed a two-stage training procedure to fit the extreme label imbalance dataset.
        * Derived a numerically stable math formulation to avoid floating point underflow calculating loss.

  - title: Applied Research Intern
    company: PingAn
    company_url: ''
    company_logo: pingan
    location: Shanghai
    date_start: '2017-05-01'
    date_end: '2017-08-31'
    description: |2-
        Lung nodule detection in CT images:

        * Achieved rank 6 out of 2887 teams in the Skylake competition sponsored by Intel and Alibaba.
        * Applied PyTorch, 3D UNet and Caffe, Faster RCNN to detect lung nodules in 1000 CT scans.
        * Used fusion method to achieve false positive reduction.

design:
  columns: '2'
---
