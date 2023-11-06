---
title: 'Triggerless data acquisition pipeline for Machine Learning based stastistical anomaly detection'
#authors:
#  - Migliorini Matteo
#  - Pazzini Jacopo
#  - Triossi Andrea
#  - Zanetti Marco
#  - Zucchetta Alberto
#author_notes:
#  - 'Equal contribution'
# - 'Equal contribution'
date: '2023-11-03'
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
 This work describes an online processing pipeline designed to identify anomalies in a continuous stream of data collected without external triggers from a particle detector. The processing pipeline begins with a local reconstruction algorithm, employing neural networks on an FPGA as its first stage. Subsequent data preparation and anomaly detection stages are accelerated using GPGPUs. As a practical demonstration of anomaly detection, we have developed a data quality monitoring application using a cosmic muon detector. Its primary objective is to detect deviations from the expected operational conditions of the detector. This serves as a proof-of-concept for a system that can be adapted for use in large particle physics experiments, enabling anomaly detection on datasets with reduced bias.

# Summary. An optional shortened abstract.
summary: "A pipeline to run anomaly detection algorithms on unfiltered
detector data"

tags:
  - Trigger
  - Online Data Processing
  - High Energy Physics
featured: false

#links:
#  - name: Custom Link
#    url: http://example.org
url_pdf: https://arxiv.org/abs/2311.02038
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

