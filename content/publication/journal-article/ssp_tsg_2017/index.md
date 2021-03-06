---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Stochastic Shortest Path Framework for Quantifying the Value and Lifetime of Battery Energy Storage Under Dynamic Pricing"
subtitle: ""
authors:
  - "**Xiaoqi Tan**"
  - Yuan Wu
  - Danny H.K. Tsang
tags: ["Smart Grid", "Optimization"]
categories: []
date: 2017-03-15T09:14:50-05:00
lastmod: 2019-11-18T09:14:50-05:00
featured: false
draft: false


links:
- icon: ieee
  icon_pack: ai
  name: IEEE Xplore
  url: "https://ieeexplore.ieee.org/document/7286849"

url_pdf: /files/papers/ssp_tsg_2017.pdf
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
publication: "IEEE Transactions on Smart Grid"
publication_short: ""

abstract: "This paper aims at quantifying the value of a lifetime-constrained battery energy storage system (BESS) operated by a consumer who faces fluctuating electricity prices. We define the lifetime of the BESS as the serving duration within which the BESSs capacity stays above a certain threshold of its initial capacity and define the value of the BESS as the total peak-shaving value within its entire lifetime. Under the assumption that the price dynamics are Markovian, we show that maximizing the average value of the BESS can be formulated as a stochastic shortest path (SSP) problem, and the average lifetime corresponds to the average number of steps before being absorbed in the SSP problem. We propose an efficient parallel value iteration algorithm to solve the proposed SSP problem with guarantees of achieving optimality and a fast convergence. We also derive a closed form expression for the average lifetime based on the principle of an embedded absorbing Markov chain. We validate our model and algorithm on a practical BESS via real price data sets from two different markets. Comparison of the computational efficiency between the standard Gauss-Seidel value iteration and our parallel algorithm is also illustrated through extensive simulation."

# Summary. An optional shortened abstract.
summary: This paper proposes a stochastic shortest path model for quantifying the value of a lifetime-constrained battery energy storage system under fluctuating electricity prices.

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
