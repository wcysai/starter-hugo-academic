---
title: 'Sampling Lovász Local Lemma for General Constraint Satisfaction Solutions in Near-Linear Time'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - KunHe
  - admin
  - YitongYin

# Author notes (optional)

date: '2022-04-04T08:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-04-04T08:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: in the 63rd IEEE Symposium on Foundations of Computer Science (FOCS 2022)

abstract: >-
  We give a fast algorithm for sampling uniform solutions of *general* constraint satisfaction problems (CSPs) in a local lemma regime. Suppose that the CSP has $n$ variables with domain size at most $q$, each constraint contains at most $k$ variables, shares variables with at most $\Delta$ constraints, and is violated with probability at most $p$ by a uniform random assignment. The algorithm returns an almost uniform satisfying assignment in expected $\mathrm{poly}(q,k,\Delta)\cdot\tilde{O}(n)$ time, as long as a local lemma condition is satisfied: $$k\cdot p\cdot q^2\cdot \Delta^5\le C_0\quad\text{for a suitably small absolute constant }C_0.$$ Previously, under similar local lemma conditions, sampling algorithms with running time polynomial in both $n$ and $\Delta$ were only known for the almost atomic case, where each constraint is violated by a small number of forbidden local configurations. The key term $\Delta^5$ in our local lemma condition also improves the previously best known $\Delta^7$ for general CSPs [JPV21b] and $\Delta^{5.714}$ for atomic CSPs, including the special case of $k$-CNF [JPV21a, HSW21].<br>
  Our sampling approach departs from previous fast algorithms for sampling LLL, which were based on Markov chains. A crucial step of our algorithm is a recursive marginal sampler that is of independent interests. Within a local lemma regime, this marginal sampler can draw a random value for a variable according to its marginal distribution, at a cost independent of the size of the CSP.

# Summary. An optional shortened abstract.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: arXiv
  url: https://arxiv.org/pdf/2204.01520
- name: FOCS_ver
  url: https://ieeexplore.ieee.org/document/9996860

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
