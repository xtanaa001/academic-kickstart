---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Optimal Charging Operation of Battery Swapping and Charging Stations with QoS Guarantee"
subtitle: ""
summary: ""
authors:
  - Bo Sun
  - "**Xiaoqi Tan**"
  - Danny H.K. Tsang
tags: ["Smart Grid"]
categories: []
date: 2018-09-15T09:14:50-05:00
lastmod: 2019-11-18T09:14:50-05:00
featured: false
draft: false


links:
- icon: ieee
  icon_pack: ai
  name: IEEE Xplore
  url: "https://ieeexplore.ieee.org/document/7286849"

url_pdf: /files/papers/bscs_QoS_tsg_2018.pdf
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

abstract: "Motivated by the urgent demand for the electric vehicle (EV) fast refueling technologies, battery swapping and charging stations (BSCSs) are envisioned as a promising solution to provide timely EV refueling services. However, inappropriate battery charging operation in BSCSs can not only incur unnecessary high charging cost but also threaten the reliability of the power grid. In this paper, we aim at obtaining an optimal charging operation policy for a single BSCS to minimize its charging cost while ensuring its quality-of-service. Leveraging the novel queueing network model, we propose to formulate the charging operation problem as a constrained Markov decision process and derive the optimal policy by the standard Lagrangian method and dynamic programming. To avoid the curse of dimensionality in practical large-scale systems, we further analyze the structure of the optimal policy and transform the dynamic programming procedure into an equivalent threshold optimization problem with a discrete separable convex objective function. Numerical results validate our theoretical analysis and the computational efficiency of our proposed algorithms. Our work also shows the impact of the system parameters (e.g., numbers of batteries and chargers) on the average cost under the optimal charging policy, which gives rich insights into the infrastructure planning of future BSCS networks."

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
