---
title: "Energy Management of Cooperative Microgrids: A Distributed Optimization Approach"
subtitle: ""
summary: ""
authors:
  - Tian Liu
  - "**Xiaoqi Tan**"
  - Bo Sun
  - Yuan Wu
  - Danny H.K. Tsang
tags: ["Smart Grid"]
categories: []
date: 2018-03-15T09:14:50-05:00
lastmod: 2019-11-18T09:14:50-05:00
featured: false
draft: false


links:
 - name: "Elsevier"
   url: "https://www.sciencedirect.com/science/article/abs/pii/S0142061517300133"

url_pdf: /files/papers/cooperative_MGs_2018.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "International Journal of Electrical Power and Energy Systems"
publication_short: ""

abstract: The cooperation of multiple networked microgrids (MGs) can alleviate the mismatch problem between distributed generation and demand and reduce the overall cost of the power system. Energy management with direct energy exchange among MGs is a promising approach for improving energy efficiency. However, existing methods on microgrid cooperation usually overlook the underlying distribution network with operating constraints (e.g., voltage tolerance and power flow constraints). Hence the results may not be applicable to actual systems. This paper studies the energy management problem of multiple MGs that are interconnected by both the direct current (DC) energy exchange network and the alternating current (AC) traditional distribution networks. In our problem, each MG is equipped with renewable energy generators as well as distributed storage devices. In order to handle the non-convex power flow constraints, we exploit the recent results of the exact optimal power flow (OPF) relaxation method which can equivalently transform the original non-convex problem into a second-order cone programming problem and efficiently determine the optimal solution successfully. The objective of our problem is to minimize the overall energy cost in a distribution network consisting of multiple MGs, with the practical operating constraints (e.g., power balance and the battery’s operational constraints) explicitly incorporated. Considering the privacy and scalability, we propose a distributed algorithm with convergence assurance based on the alternating direction method of multipliers (ADMM). We also implement our method based on the model predictive control (MPC) approach in order to handle the forecasting errors of the renewable energy generation. Simulations are made for different MG exchange topologies on three radial distribution network testbeds. Numerical results demonstrate that certain topologies are more favorable than others, and the cooperation strategy for the energy exchange is significantly affected by the MGs’ locations in the distribution network.

# Summary. An optional shortened abstract.
# summary: We study the mechanism design for online allocation of resources. A single supplier who allocates capacity-limited resources (e.g., computing cycles, network bandwidth, energy, etc. ) to requests that arrive in a sequential and arbitrary manner.

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point:
  preview_only: true

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
