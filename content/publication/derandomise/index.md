---
title: 'Towards derandomising Markov Chain Monte Carlo'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Weiming Feng
  - Heng Guo
  - admin
  - Jiaheng Wang
  - YitongYin

# Author notes (optional)

date: '2023-07-01T08:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-07-01T08:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: To appear in the 64th IEEE Symposium on Foundations of Computer Science (FOCS 2023)

abstract: We present a new framework to derandomise certain Markov chain Monte Carlo (MCMC) algorithms. As in MCMC, we first reduce counting problems to sampling from a sequence of marginal distributions. For the latter task, we introduce a method called coupling towards the past that can, in logarithmic time, evaluate one or a constant number of variables from a stationary Markov chain state. Since there are at most logarithmic random choices, this leads to very simple derandomisation. We provide two applications of this framework, namely efficient deterministic approximate counting algorithms for hypergraph independent sets and hypergraph colourings, under local lemma type conditions matching, up to lower order factors, their state-of-the-art randomised counterparts.

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
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

