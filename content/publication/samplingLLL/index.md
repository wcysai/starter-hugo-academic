---
title: 'Sampling Lovász Local Lemma for General Constraint Satisfaction Solutions in Near-Linear Time'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Kun He
  - admin
  - YitongYin

# Author notes (optional)

date: '2022-04-04T08:00:00Z'
doi: '10.1109/FOCS54457.2022.00021'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-04-04T08:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: in the 63rd IEEE Symposium on Foundations of Computer Science (FOCS 2022)

abstract: We give a fast algorithm for sampling uniform solutions of *general* constraint satisfaction problems (CSPs) in a local lemma regime. The expected running time of our algorithm is near-linear in $n$ and a fixed polynomial in $\Delta$, where $n$ is the number of variables and $\Delta$ is the max degree of constraints. Previously, up to similar conditions, sampling algorithms with running time polynomial in both $n$ and $\Delta$, only existed for the almost atomic case, where each constraint is violated by a small number of forbidden local configurations.  Our sampling approach departs from all previous fast algorithms for sampling LLL, which were based on Markov chains. A crucial step of our algorithm is a recursive marginal sampler that is of independent interests.  Within a local lemma regime, this marginal sampler can draw a random value for a variable according to its marginal distribution, at a local cost independent of the size of the CSP.

# Summary. An optional shortened abstract.

tags: []

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
url_slides: 'Sampling LLL-FOCS.pdf'
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

