---
title: 'Machine Learning muon identification on FPGA for the CMS experiment'


# Summary. An optional shortened abstract.
#summary: "Thesis for Master's Degree in Physics of Data"

tags:
  - Master
  - Machine Learning
  - FPGA
  - Particle Reconstruction
  - CMS
  - HEP
featured: false

show_date: false

#links:
#  - name: Custom Link
#    url: http://example.org
#url_pdf: https://arxiv.org/abs/2105.04428
#url_code:
#url_dataset:
#url_poster: 
#url_project:
#url_slides:
#url_source:
#url_video:

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

<p align=justify>
The Drift Tube (DT) muon detector of the CMS experiment at CERN is one of the main elements for the identification and selection of interesting physics events at CMS.
Being able to identify and measure the properties of a muon track is thus paramount for the efficient reconstruction and selection of all kinds of rare and important physics processes, including Higgs boson decays, and possibly yet-to-be-observed new particles.
</p>

<p align=justify>
Programmable hardware devices (FPGAs) do implement complex algorithms to produce a reliable identification and selection, within a very short and finite latency, of the order of 1 microsecond.
Recently, flexible tools (such as HLS4ML) have become available to develop Machine Learning models tailored to the application on hardware devices, allowing to deploy them on commercial FPGAs.
ML methods are commonly exploited to perform denoising tasks and pattern recognition and are characterized by extremely fast evaluation time.
These features make the application of ML an excellent alternative, with possibly better performance than fully-analytic algorithms both in terms of efficiency and latency.
The ML models will first be designed and validated in Software using dedicated simulations, while balancing their accuracy with the simulated performances on hardware, both in terms of latency and complexity.
The successfully trained models will be implemented on commercial FPGAs, where real-world performances can be evaluated with the help of data streams from mock-up CMS DT detectors.
</p>

Supervisor: <a href="../../people/pazzini-jacopo">Jacopo Pazzini</a>
