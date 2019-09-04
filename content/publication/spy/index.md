---
title: "Asynchronous Distributed Learning with Sparse Communications and Identification"
authors:
- admin
- Franck Iutzeler
- Jerome Malick
- Massih-Reza Amini
date: "2018-12-10T00:00:00Z"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]


abstract: In this paper, we present an asynchronous optimization algorithm for distributed learning, that efficiently reduces the communications between a master and working machines by randomly sparsifying the local updates. This sparsification allows to lift the communication bottleneck often present in distributed learning setups where computations are performed by workers on local data while a master machine coordinates their updates to optimize a global loss. We prove that despite its sparse asynchronous communications, our algorithm allows for a fixed stepsize and benefits from a linear convergence rate in the strongly convex case. Moreover, for $\ell_1$-regularized problems, this algorithm identifies near-optimal sparsity patterns, so that all communications eventually become sparse. We furthermore leverage on this identification to improve our sparsification technique. We illustrate on real and synthetic data that this algorithm converges faster in terms of data exchanges.

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://arxiv.org/pdf/1812.03871.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

---


