---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Optimal Scheduling of Battery Charging Stations Serving Electric Vehicles Based on Battery Swapping"
subtitle: ""
summary: ""
authors:
  - "**Xiaoqi Tan**"
  - Guannan Qu
  - Bo Sun
  - Na Li
  - Danny H.K. Tsang
tags: []
categories: []
date: 2019-09-15T09:14:50-05:00
lastmod: 2019-11-18T09:14:50-05:00
featured: false
draft: false


links:
- icon: ieee
  icon_pack: ai
  name: IEEE Xplore
  url: "https://ieeexplore.ieee.org/document/8076716"

url_pdf: /files/papers/optimal_bcs_tsg_2019.pdf
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

abstract: "A battery charging station (BCS) is a charging facility that supplies electric energy for recharging electric vehicles’  depleted  batteries  (DBs).  A  BCS  has  a  certain  numberof  charging  bays  and  maintains  a  dynamic  inventory  of  fullycharged  batteries  (FBs).  This  paper  studies  a  BCS  schedul-ing  (BCSS)  problem  whose  target  is  to  schedule  the  chargingprocesses of the charging bays such that the charging cost is min-imized  while  satisfying  the  FB  demand.  Specifically,  the  BCSSproblem  has  two  types  of  operations:  1)  loading  DBs  into  thecharging  bays  and  then  unloading  them  to  the  FB  inventorywhen they are fully charged and 2) controlling the charging rateof  each  charging  bay.  We  formulate  the  BCSS  problem  as  amixed-integer program with quadratic battery degradation cost.A generalized benders decomposition algorithm is then developedto  solve  the  problem  efficiently.  The  salience  of  the  developedalgorithm is that: 1) each charging bay can solve its own subprob-lem separately and 2) each subproblem can be further partitionedinto  multiple  independent  and  identically  structured  quadraticprogramming  problems,  and  thus  the  algorithm  facilitates  anefficient parallel implementation. We perform extensive real datasimulation  to  validate  the  optimization  model  and  demonstratethe  efficiency  of  the proposed  algorithm."

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
