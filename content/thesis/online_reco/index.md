---
title: 'Online particle reconstruction with cluster and accelerated computing at CMS'


# Summary. An optional shortened abstract.
#summary: "Thesis for Master's Degree in Physics of Data"

tags:
  - Master
  - Computing
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
The CMS experiment at CERN will undergo major upgrades in the near future, including a completely redesigned data readout and acquisition systems for many sub-detectors.
The muon detector Drift Tube (DT) chambers of CMS are currently testing a new set of read-out boards, capable of producing a continuous stream of signals at 40 MHz.
Dedicated algorithms are run online on programmable hardware devices (FPGAs) to elaborate these signals and identify and reconstruct local "tracklets" (or segments) compatible with the passage of a particle through each DT chamber.
Currently, these segments are then passed to further stages of FPGA boards to attempt the reconstruction of the entire muon trajectory through the whole CMS detector. 
Depending on the quality of the reconstructed tracks the CMS Trigger system will decide whether to retain or discard the entire collision.
The reconstruction performances are however capped by a set of limitations induced by the algorithms we are currently capable of implementing in hardware.
</p>

<p align=justify>
A new data acquisition system is currently being tested in CMS to bypass the hardware stages and move all data to clusters of computing resources.
The thesis' activities will focus on this new paradigm. 
Free of the hardware limitations, alternative processing is possible in Software, by exploiting cluster computing and accelerators such as GPUs.
A redesign of the muon reconstruction algorithms is thus required to be able to exploit the continuous stream of data. 
The performance of the reconstruction is going to be compared with the current existent ones based on FPGAs, and with the ones performed offline on the fraction of data selected by the CMS trigger system.
</p>

Supervisor: <a href="../../people/pazzini-jacopo">Jacopo Pazzini</a>
