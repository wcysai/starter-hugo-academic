---
title: 'Local Gibbs sampling beyond local uniformity'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - HongyangLiu
  - admin
  - YitongYin

# Author notes (optional)

date: '2025-10-01T08:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-10-01T08:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: in the 37th ACM-SIAM Symposium on Discrete Algorithms (SODA 2026)

abstract: >-
  Local samplers are algorithms that generate random samples based on local queries to high-dimensional distributions, ensuring the samples follow the correct induced distributions while maintaining time complexity that scales locally with the query size. These samplers have broad applications, including deterministic approximate counting [He, Wang, Yin, SODA '23; Feng et al., FOCS '23], sampling from infinite or high-dimensional Gibbs distributions [Anand, Jerrum, SICOMP '22; He, Wang, Yin, FOCS '22], and providing local access to large random objects [Biswas, Rubinfeld, Yodpinyanee, ITCS '20].<br>
  In this work, we present local samplers for Gibbs distributions of spin systems. Specifically, we design linear-time local samplers for:<br>
  • spin systems with soft constraints, including the first local sampler for near-critical Ising models;<br>
  • truly repulsive spin systems, represented by the first local sampler for uniform proper $q$-colorings, with $q=O(\Delta)$ colors on graphs with maximum degree $\Delta$.<br>
  These local samplers are efficient beyond the “local uniformity” threshold, which imposes unconditional marginal lower bounds—a key assumption required by all prior local samplers. Our results show that, in general, local sampling is not significantly harder than global sampling for spin systems. As an application, our results also imply local algorithms for probabilistic inference in the same near-critical regimes.
# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: arXiv
  url: https://arxiv.org/pdf/2502.10795
- name: SODA_ver
  url: https://epubs.siam.org/doi/10.1137/1.9781611978971.41

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: 'poster.pdf'
url_project: ''
url_slides: 'SODA26.pdf'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
