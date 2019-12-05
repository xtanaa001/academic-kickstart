---
title: "Online Combinatorial Auction for Resource Allocation with Supply Costs and Capacity Limits"
authors:
 - "**Xiaoqi Tan**"
 - Alberto Leon-Garcia
 - Yuan Wu
 - Danny H.K. Tsang
tags: 
 - Mechanism Design
 - Online Algorithms
 - Cloud/Edge Computing
 - Algorithmic Game Theory
categories: []
date: "2019-10-17T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2019-11-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Journal of Selected Areas in Communication"
publication_short: ""

abstract: We study a general online combinatorial auction problem in algorithmic mechanism design. A provider allocates multiple types of capacity-limited resources to customers that arrive in a sequential and arbitrary manner. Each customer has a private valuation function on bundles of resources that she can purchase (e.g., a combination/package of different resources such as CPU and RAM in cloud computing). The provider charges payment from customers who purchase a bundle of resources and incurs an increasing supply cost with respect to the total resource allocated. The goal is to maximize the social welfare, namely, the total valuation of customers for their purchased bundles, minus the total supply cost of the provider for all the resources that have been allocated. We adopt the competitive analysis framework and provide posted-pricing mechanisms with optimal competitive ratios.  Our pricing mechanism is optimal in the sense that no other online algorithms can achieve a better competitive ratio. We validate the theoretic results via empirical studies of online resource allocation in cloud computing. Our numerical results demonstrate that the proposed pricing mechanism is competitive and robust against system uncertainties and outperforms existing benchmarks.

# Summary. An optional shortened abstract.
summary: This paper studies a general online combinatorial auction problem in algorithmic mechanism design. A posted price mechanism is proposed in this paper and outperforms the-state-of-the-art. 

# tags:
# - Source Themes
featured: true


links:
  -  icon: ieee
     icon_pack: ai
     name: IEEE Xplore
     url: ""
  - icon: arxiv
    icon_pack: ai
    name: arXiv Report
    url: ""

url_pdf:  /files/papers/online_combinatorial_auction_2020.pdf
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
  caption:  # 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ["online_combinatorial_auction"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example

# {{% alert note %}}
# Below Please find the major results of this paper.
# {{% /alert %}}
---