---
title: '*Modeling hadronization using machine learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
#authors:
#  - admin
#  - Robert Ford

authors:
  - Phil Ilten
  - Tony Menzo
  - admin
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


date: '2023-03-01'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['Journal paper']

# Publication name and optional abbreviated publication name.
publication: SciPost Physics
publication_short: SciPost Physics

abstract: We present the first steps in the development of a new class of hadronization models utilizing machine learning techniques. We successfully implement, validate, and train a conditional sliced-Wasserstein autoencoder to replicate the PYTHIA generated kinematic distributions of first-hadron emissions, when the Lund string model of hadronization implemented in PYTHIA is restricted to the emissions of pions only. The trained models are then used to generate the full hadronization chains, with an IR cutoff energy imposed externally. The hadron multiplicities and cumulative kinematic distributions are shown to match the PYTHIA generated ones. We also discuss possible future generalizations of our results.
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

url_pdf: 'https://scipost.org/SciPostPhys.14.3.027'
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



