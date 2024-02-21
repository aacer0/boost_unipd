--- 
title: Fast data transmission protocol on FPGA
summary: ' '
tags:
  - Hardware
date: '2016-03-01T00:00:00Z'
show_date: false
# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  #caption: Photo by rawpixel on Unsplash
  focal_point: Smart

# links:
#   - icon: envelope
#     icon_pack: fas
#     url: 'mailto:andrea.triossi@unipd.it'
#   #- icon: twitter
#   #  icon_pack: fab
#   #  url: https://twitter.com/GeorgeCushen
#   #- icon: google-scholar
#   #  icon_pack: ai
#   #  url: https://scholar.google.co.uk/citations?user=sIwtMXoAAAAJ
#   - icon: github
#     icon_pack: fab
#     url: https://github.com/aacer0
#   - icon: google-scholar
#     icon_pack: ai
#     url: https://scholar.google.com.sg/citations?user=tRn2z8cAAAAJ&hl=en
# url_code: ''
# url_pdf: ''
# url_slides: ''
# url_video: ''


---

The constant trend in producing larger and larger dataset is evident in almost every field of experimental physics. This need is heightened in experiments that, for reducing inefficiencies or for not being constrained by restricted latency budgets, decide to run without a hardware trigger system. The processing power is of paramount importance for the computing farm called to process the dataset eventually, but an inefficient data movement often weakens it. FEROCE aims to improve the typical paradigm used in the data acquisition systems (DAQs) of physics experiments easing the back-end electronics. Thanks to the early adoption of efficient network protocol, the front-end electronics creates a direct channel with the memory of the DAQ computing nodes. Beyond the front-end the entire DAQ can be built by only COTS hardware exploiting all the assets of a well proven de facto standard technology. We intend to implement in FPGA a small appliance of the RoCEv2 stack in order to be able to deploy it on an FPGA of the size typically adopted in the front-end electronics of a physics experiment. We would also extend the usual range of target FPGAs including the flash-based ones for employing the developed core on harsh radiation environments like an experimental hall of a HEP experiment. The main result of FEROCE will be the delivery of an FPGA core, with a small resource footprint, that manages the transmission of a data buffer over a RoCEv2 network. The core will be made as much portable as possible (agnostic to the FPGA vendor) in order to be directly deployable on the front-end electronics of a wide range of experiments. Finally, its performances will be evaluated in a network based on commodity hardware.
