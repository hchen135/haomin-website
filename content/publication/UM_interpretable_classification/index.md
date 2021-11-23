---
title: "An Interpretable Algorithm for Uveal Melanoma Subtyping from Whole Slide Cytology Images"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- TY Alvin liu
- Catalina Gomez
- Zelia Correa
- Mathias Unberath

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-08-13T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *ICML workshop on Interpretable Machine Learning in Healthcare*
publication_short: In *IMLH*

abstract: Algorithmic decision support is rapidly becoming a staple of personalized medicine, especially for high-stakes recommendations in which access to certain information can drastically alter the course of treatment, and thus, patient outcome; a prominent example is radiomics for cancer subtyping. Because in these scenarios the stakes are high, it is desirable for decision systems to not only provide recommendations but supply transparent reasoning in support thereof. For learning-based systems, this can be achieved through an interpretable design of the inference pipeline. Herein we describe an automated yet interpretable system for uveal melanoma subtyping with digital cytology images from fine needle aspiration biopsies. Our method embeds every automatically segmented cell of a candidate cytology image as a point in a 2D manifold defined by many representative slides, which enables reasoning about the cell-level composition of the tissue sample, paving the way for interpretable subtyping of the biopsy. Finally, a rule-based slide-level classification algorithm is trained on the partitions of the circularly distorted 2D manifold. This process results in a simple rule set that is evaluated automatically but highly transparent for human verification. On our in house cytology dataset of 88 uveal melanoma patients, the proposed method achieves an accuracy of 87.5% that compares favorably to all competing approaches, including deep "black box" models. The method comes with a user interface to facilitate interaction with cell-level content, which may offer additional insights for pathological assessment.

# Summary. An optional shortened abstract.
summary: An interpretable classification of genetic information for UM prognostication with cell composition analysis.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Label hierarchy for PLCO CXR dataset.'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
