---
abstract: Graph neural networks (GNNs) have shown state-of-the-art performances in various applications. However, GNNs often struggle to capture long-range dependencies in graphs due to oversmoothing. In this paper, we generalize the concept of oversmoothing from undirected to directed graphs. To this aim, we extend the notion of Dirichlet energy by considering a directed symmetrically normalized Laplacian. As vanilla graph convolutional networks are prone to oversmooth, we adopt a neural graph ODE framework. Specifically, we propose fractional graph Laplacian neural ODEs, which describe non-local dynamics. We prove that our approach allows propagating information between distant nodes while maintaining a low probability of long-distance jumps. Moreover, we show that our method is more flexible with respect to the convergence of the graph's Dirichlet energy, thereby mitigating oversmoothing. We conduct extensive experiments on synthetic and real-world graphs, both directed and undirected, demonstrating our method's versatility across diverse graph homophily levels. 
slides: example
url_pdf: https://arxiv.org/pdf/2305.13084.pdf
publication_types:
  - "1"
authors:
  - admin
  - Raffaele Paolino
  - Aras Bacho
  - Gitta Kutyniok
summary: We introduce the fractional graph Laplacian neural ODE, which alleviates oversmoothing and is well-suited for both directed and undirected graphs, as well as various levels of homophily."
url_dataset: ""
url_project: ""
author_notes:
  - Equal contribution
  - Equal contribution
publication_short: NeurIPS 2023
url_source: ""
url_video: ""
publication: Advances in Neural Information Processing Systems 2023
featured: false
date: 2023-10-01T00:00:00Z
url_slides: ""
title: "A Fractional Graph Laplacian Approach to Oversmoothing"
tags:
  - Source Themes
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
publishDate: 2023-10-01T00:00:00Z
url_poster: ""
url_code: ""
doi: ""
---
