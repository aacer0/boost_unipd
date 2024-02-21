---
title: 'Muon trigger with fast Neural Networks on FPGA, a demonstrator'
authors:
 - Migliorini Matteo
 - Pazzini Jacopo
 - Triossi Andrea
 - Zanetti Marco
 - Zucchetta Alberto
#author_notes:
#  - 'Equal contribution'
# - 'Equal contribution'
date: '2021-05-10'
doi: '10.48550/arXiv.2105.04428'

# Schedule page publish date (NOT publication's date).
#publishDate: '2022-08-01'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
#publication: In *Nuclear Instruments and Method A*
#publication_short: 

abstract: >
 The online reconstruction of muon tracks in High Energy Physics experiments is a highly demanding task, typically performed with programmable logic boards, such as FPGAs. Complex analytical algorithms are executed in a quasi-real-time environment to identify, select and reconstruct local tracks in often noise-rich environments. A novel approach to the generation of local triggers based on an hybrid combination of Artificial Neural Networks and analytical methods is proposed, targeting the muon reconstruction for drift tube detectors. The proposed algorithm exploits Neural Networks to solve otherwise computationally expensive analytical tasks for the unique identification of coherent signals and the removal of the geometrical ambiguities. The proposed approach is deployed on state-of-the-art FPGA and its performances are evaluated on simulation and on data collected from cosmic rays.

# Summary. An optional shortened abstract.
summary: "A neural network based algorithm implemented on firmware to
reconstruct  muon stubs with Drift Tubes chambers"

tags:
  - Trigger
  - Online Data Processing
  - High Energy Physics
featured: false

#links:
#  - name: Custom Link
#    url: http://example.org
url_pdf: https://arxiv.org/abs/2105.04428
url_code:
url_dataset:
url_poster: 
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption:
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

