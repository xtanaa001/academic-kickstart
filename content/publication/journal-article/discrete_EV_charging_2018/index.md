---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Optimal Scheduling for Electric Vehicle Charging With Discrete Charging Levels in Distribution Grid"
subtitle: ""
summary: ""
authors:
  - Bo Sun
  - Zhe Huang
  - "**Xiaoqi Tan**"
  - Danny H.K. Tsang
tags: ["Smart Grid"]
categories: []
date: 2018-03-15T09:14:50-05:00
lastmod: 2019-11-18T09:14:50-05:00
featured: false
draft: false


links:
 - icon: ieee
   icon_pack: ai
   name: IEEE Xplore
   url: "https://ieeexplore.ieee.org/document/7460201"

url_pdf: /files/papers/discrete_EV_charging_2018.pdf
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

abstract: To accommodate the increasing electric vehicle (EV) penetration in distribution grid, coordinated EV charging has been extensively studied in the literature. However, most of the existing works optimistically consider the EV charging rate as a continuous variable and implicitly ignore the capacity limitation in distribution transformers, which both have great impact on the efficiency and stability of practical grid operation. Towards a more realistic setting, this paper formulates the EV coordinated discrete charging problem as two successive binary programs. The first one is designed to achieve a desired aggregate load profile (e.g., valley-filling profile) at the distribution grid level while taking into account the capacity constraints of distribution transformers. Leveraging the properties of separable convex function and total unimodularity, the problem is transformed into an equivalent linear program, which can be solved efficiently and optimally. The second problem aims to minimize the total number of on-off switchings of all the EVs' charging profiles while preserving the optimality of the former problem. We prove the second problem is NP-hard and propose a heuristic algorithm to approximately achieve our target in an iterative manner. Case studies confirm the validity of our proposed scheduling methods and indicate our algorithm's potential for real-time implementations.

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
projects: ["electric_vehicle_networks"]
---
