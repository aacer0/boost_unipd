---
title: 'Towards Tensor Network Models for Low-Latency Jet Tagging on FPGAs'
authors:
 - Lorenzo Borella, Alberto Coppi, Jacopo Pazzini, Andrea Triossi
#author_notes:
#  - 'Equal contribution'
# - 'Equal contribution'
date: '2026-01-15'
doi: ' doi.org/10.48550/arXiv.2601.10801'



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

 We present a systematic study of Tensor Network (TN) models Matrix Product States (MPS) and Tree Tensor Networks (TTN)  for real-time jet tagging in high-energy physics, with a focus on low-latency deployment on Field Programmable Gate Arrays (FPGAs). Motivated by the strict requirements of the HL-LHC Level-1 trigger system, we explore TNs as compact and interpretable alternatives to deep neural networks. Using low-level jet constituent features, our models achieve competitive performance compared to state-of-the-art deep learning classifiers. We investigate post-training quantization to enable hardware-efficient implementations without degrading classification performance or latency. The best-performing models are synthesized to estimate FPGA resource usage, latency, and memory occupancy, demonstrating sub-microsecond latency and supporting the feasibility of online deployment in real-time trigger systems. Overall, this study highlights the potential of TN-based models for fast and resource-efficient inference in low-latency environments
 
summary: "Quantum inspired algorithm for jet tagging deployed on FPGA
for triger applications"

tags:
  - Quantum algorithms
  - FPGA
  - HEP
featured: false

#links:
#  - name: Custom Link
#    url: http://example.org
url_pdf: https://arxiv.org/pdf/2601.10801
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

