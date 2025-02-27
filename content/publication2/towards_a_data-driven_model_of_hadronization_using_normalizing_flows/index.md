---
title: '*Towards a data-driven model of hadronization using normalizing flows'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
#authors:
#  - admin
#  - Robert Ford

authors:
  - Christian Bierlich
  - Phil Ilten
  - Tony Menzo
  - Stephen Mrenna
  - Manuel Szewc
  - Michael K. Wilkinson
  - Ahmed Youssef
  - Jure Zupan


# Author notes (optional)
author_notes:
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''


date: '2023-11-01'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['preprint']

# Publication name and optional abbreviated publication name.
publication: Submitted to SciPost Physics
publication_short: Submitted to SciPost Physics

abstract: We introduce a model of hadronization based on invertible neural networks that faithfully reproduces a simplified version of the Lund string model for meson hadronization. Additionally, we introduce a new training method for normalizing flows, termed MAGIC, that improves the agreement between simulated and experimental distributions of high-level (macroscopic) observables by adjusting single-emission (microscopic) dynamics. Our results constitute an important step toward realizing a machine-learning based model of hadronization that utilizes experimental data during training. Finally, we demonstrate how a Bayesian extension to this normalizing-flow architecture can be used to provide analysis of statistical and modeling uncertainties on the generated observable distributions.
#This paper introduces two novel machine learning based approaches to improve hadron-level simulation by integrating experimental observables; **M**icroscopic **A**lterations **G**enerated from **I**R **C**ollections (**MAGIC**), which fine-tunes normalizing flows, pre-trained on simulated data from PYTHIA, on experimental observables, and the **C**ollective **R**eweighting **M**ethod (**CRM**), which reweights existing fragmentation functions to match experimental observables with a two-step procedure that makes use of a observable-level classifier and hadron-level particle cloud-based regressor. Both methods show a promising direction towards data-driven models for hadronization.

# Summary. An optional shortened abstract.
summary: In this paper we present ....

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2311.09296'
url_code: 'https://gitlab.com/uchep/mlhad'
#url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_poster: ''
url_project: 'https://uchep.gitlab.io/mlhad-docs/'
#url_slides: ''
#url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---



