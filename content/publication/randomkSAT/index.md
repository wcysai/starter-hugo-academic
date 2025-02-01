---
title: 'Counting random k-SAT near the satisfiability threshold'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zongchen Chen
  - Aditya Lonkar
  - admin
  - Kuang Yang
  - YitongYin

# Author notes (optional)

date: '2025-02-21T08:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-04-04T08:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: to appear in the 57th IEEE Symposium on Foundations of Computer Science (STOC 2025)

abstract: We present efficient counting and sampling algorithms for random $k$-SAT when the clause density satisfies $\alpha \leq 2^k/\text{poly}(k)$. In particular, the exponential term $2^k$ matches the satisfiability threshold $\Theta(2^k)$ for the existence of a solution and the (conjectured) algorithmic threshold $2^k(\ln k)/k$ for efficiently finding a solution. Previously, the best-known counting and sampling algorithms required far more restricted densities $\alpha\lesssim 2^k/3$ [He, Wu, Yang, SODA '23]. Notably, our result goes beyond the lower bound $d\gtrsim 2^k/2$ for worst-case $k$-SAT with bounded-degree $d$ [Bezáková et al, SICOMP '19], showing that for counting and sampling, the average-case random $k$-SAT model is computationally much easier than the worst-case model. At the heart of our approach is a new refined analysis of the recent novel coupling procedure by [Wang, Yin, FOCS '24], utilizing the structural properties of random constraint satisfaction problems (CSPs). Crucially, our analysis avoids reliance on the $2$-tree structure used in prior works, which cannot extend beyond the worst-case threshold $2^k/2$. Instead, we employ a witness tree similar to that used in the analysis of the Moser-Tardos algorithm [Moser, Tardos, JACM '10] for the Lovász Local lemma, which may be of independent interest. Our new analysis provides a universal framework for efficient counting and sampling for random atomic CSPs, including, for example, random hypergraph colorings. At the same time, it immediately implies as corollaries several structural and probabilistic properties of random CSPs that have been widely studied but rarely justified, including replica symmetry and non-reconstruction.

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

