---
title: 'Stability Dichotomies for Boolean Constraint Satisfaction Problems'

authors:
  - admin
  - YuichiYoshida

date: '2026-09-26T08:27:04Z'
publishDate: '2026-09-26T08:27:04Z'
doi: ''

# 3 = Preprint / Working Paper
publication_types: ['3']
publication: 'Preprint'

abstract: >-
  We study the stability of Boolean constraint satisfaction problems (CSPs) through the notion of average sensitivity (Varma and Yoshida, SODA 2021; SICOMP 2023). It measures the expected $1$-Wasserstein distance between an algorithm's output distributions before and after the deletion of a uniformly chosen constraint, using the unnormalized Hamming metric.<br>
  We establish two dichotomies for every finite Boolean constraint language $\Gamma$, where $n\geq 2$ denotes the number of variables in an instance. For stable solvability, exactly one of the following holds:<br>
  $\bullet$ either there is an algorithm that solves $\mathrm{CSP}(\Gamma)$ and has average sensitivity $O_{\Gamma}(1)$ for all satisfiable instances;<br>
  $\bullet$ or every algorithm that solves $\mathrm{CSP}(\Gamma)$ has average sensitivity $\Omega_{\Gamma}(n)$ on satisfiable instances of arbitrarily large $n$.<br>
  The first alternative holds if and only if $\Gamma$ has finite duality: unsatisfiability can be witnessed on a bounded number of variables.<br>
  For stable approximability, where a $(1-\varepsilon)$-approximation violates at most an $\varepsilon$-fraction of the constraints in expectation, exactly one of the following holds:<br>
  $\bullet$ either for every $\varepsilon\in(0,1]$, there is an algorithm that $(1-\varepsilon)$-approximates $\mathrm{CSP}(\Gamma)$ with average sensitivity $O_{\Gamma}(\varepsilon^{-1}\log n)$ for all satisfiable instances;<br>
  $\bullet$ or there exists $\varepsilon_{\Gamma}\in(0,1]$ such that every algorithm that $(1-\varepsilon_{\Gamma})$-approximates $\mathrm{CSP}(\Gamma)$ has average sensitivity $\Omega_{\Gamma}(n)$ on satisfiable instances of arbitrarily large $n$.<br>
  The first alternative holds if and only if $\Gamma$ has bounded width: local consistency checks on bounded sets of variables detect unsatisfiability.

# Keep preprints out of any Featured Publications widget.
featured: false

links:
  - name: arXiv
    url: https://arxiv.org/abs/2609.32357

url_pdf: 'https://arxiv.org/pdf/2609.32357'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

projects: []
slides: ''
---
