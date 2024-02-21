---
title: 'A horizontally scalable online processing system for trigger-less data acquisition'
authors:
 - Migliorini Matteo
 - Pazzini Jacopo
 - Triossi Andrea
 - Zanetti Marco
 - Zucchetta Alberto
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'
date: '2022-08-01'
doi: '10.1016/j.nima.2022.166869'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-08-01'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Nuclear Instruments and Method A*
publication_short: 

abstract: >
  The vast majority of high energy physics experiments rely on data acquisition and hardware-based trigger systems performing a number of stringent selections before storing data for offline analysis. The online reconstruction and selection performed at the trigger level are bound to the synchronous nature of the data acquisition system, resulting in a trade-off between the amount of data collected and the complexity of the online reconstruction performed. Exotic physics processes, such as long-lived and slow-moving particles, are rarely targeted by online triggers as they require complex and nonstandard  online reconstruction, usually incompatible with the time constraints of most data acquisition systems. The online trigger selection can thus impact as one of the main limiting factors to the experimental reach for exotic signatures. Alternative data acquisition solutions based on the continuous and asynchronous processing of the stream of data from the detectors are therefore foreseeable as a way to extend the experimental physics reach. Trigger-less data readout systems, paired with efficient streaming data processing solutions, can provide a viable alternative. In this document, an end-to-end implementation of a fully trigger-less data acquisition and online data processing system is discussed. An easily scalable and deployable implementation of such an architecture is proposed, based on open-source distributed computing frameworks capable of performing asynchronous online processing of streaming data. The proposed schema can be suitable for deployment as a fully integrated data acquisition system for small-scale experimental apparatus, or to complement the trigger-based data acquisition systems of larger experiments. A muon telescope setup consisting of a set of gaseous detectors is used as the experimental development testbed in this work, and a fully integrated online processing pipeline deployed on cloud computing resources is implemented and described.

# Summary. An optional shortened abstract.
summary: "A demonstrator for a full-fledged infrastracture for
trigger-less data acquisition and heterogeneous processing"

tags:
  - Data Acquisition
  - Trigger
  - Online Data Processing
  - High Energy Physics
featured: false

#links:
#  - name: Custom Link
#    url: http://example.org
url_pdf: https://arxiv.org/abs/2111.05155
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
slides:
---

