---
title: Conference talk at Pheno2023
subtitle: Normalizing flows and uncertainty quantification in hadronization simulations

event: Pheno 2023
event_url: https://indico.cern.ch/event/1218225/contributions/5380933/

location: University of Pittsburgh, Pittsburgh, Pennsylvania, United States
#address:
#  street: 450 Serra Mall
#  city: Stanford
#  region: CA
#  postcode: '94305'
#  country: United States

summary: Talk titled "Normalizing flows and uncertainty quantification in hadronization simulations" at the 2023 Phenomenology Symposium hosted by the University of Pittsburgh in Pittsburgh, Pennsylvania, United States.

abstract: The hadronization process plays a crucial role in Monte Carlo event generators, where quarks and gluons are combined into observable hadrons. However, while current phenomenological models have been quite successful overall in simulating this process, there remain phenomenological areas where they still lack accuracy in describing the underlying physics. Recent research has taken a new approach by utilizing machine-learning (ML) techniques based on generative models for simulating the hadronization process. However, the recently presented architectures have their own set of limitations. In this talk, we present an updated version of our MLHad pipeline that overcomes most of the limitations by incorporating normalizing flows (NFs). Our updated approach conditions NFs on different hadron masses and initial configuration energies, which in principle enables the emission of different mesons. Furthermore, the utilization of NFs grants us access to the kinematical probability distribution of the generated mesons. This allows for the implementation of a reweighting technique, which assigns a weight to each emitted meson, enabling us to estimate the uncertainties associated with the process. We demonstrate the capability of the reweighting technique to evaluate the uncertainty of our model.



# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2023-05-08'
#date_end: '2030-06-01T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
#publishDate: '2017-01-01T00:00:00Z'

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#  focal_point: Right

links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects:
#  - example
---

