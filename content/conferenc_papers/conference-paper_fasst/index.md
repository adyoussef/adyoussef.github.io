---
title: 'FASST, Few-Shot Abstractive Summarization for Style Transfer'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
#authors:
#  - admin
#  - Robert Ford
authors:
  - Omar Alsayed 
  - Chloe Muncy 
  - admin 
  - Ryan Green


# Author notes (optional)
author_notes:
  - ''
  - 'Equal Contribution'
  - 'Equal Contribution'
  - ''


date: '2023-09-01'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: ICNLP
publication_short: ICNLP

abstract: Unsupervised text style transfer methods aim to transfer the style of the text without affecting its fundamental meaning using non-parallel data. Although previous work has explored few-shot learning for this task, incorporating few-shot abstractive summarization and its benefits have not yet been explored. Hence, we propose a novel unsupervised text style transfer approach using few-shot abstractive summarization. In our method, we infer a vector space embedding for the corpora and align the source-target embeddings using their vector space centroids. A set of nearest neighbors is retrieved for every source text unit from the target style based on their semantic similarity in the aligned vector space. Multiple subsets of nearest neighbors are extracted and summarized using a language model with a reranking procedure to optimize the style transfer quality, which achieves state-of-the-art results on automatic evaluation metrics. 


# Summary. An optional shortened abstract.
summary: The paper introduces a novel unsupervised text style transfer method using few-shot abstractive summarization. This approach aligns vector space embeddings of source and target texts, selects nearest neighbors based on semantic similarity, and reranks the summarization. This method significantly improves style transfer quality and achieves soa results in automatic evaluation metrics. 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10236629'
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_poster: ''
#url_project: 'https://galdegheri.github.io/diffbending/'
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



