---
title: "Mechanism Design for Online Resource Allocation: A Unified Approach"
authors:
 - "**Xiaoqi Tan**"
 - Alberto Leon-Garcia
 - Bo Sun
 - Yuan Wu
 - Danny H.K. Tsang

tags: 
 - Mechanism Design
 - Online Algorithms
 - Algorithmic Game Theory
date: "2019-11-10T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2019-11-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Preprint"
publication_short: ""

abstract: This paper concerns the mechanism design for online resource allocation in a strategic setting. In this setting, a single supplier allocates capacity-limited resources to requests that arrive in a sequential and arbitrary manner. Each request is associated with an agent who may act selfishly to misreport the requirement and valuation of her request. The supplier charges payment from agents whose requests are satisfied, but incurs a load-dependent supply cost. The goal is to design an incentive compatible online mechanism, which determines not only the resource allocation of each request, but also the payment of each agent, so as to (approximately) maximize the social welfare (i.e., aggregate valuations minus supply cost). We study this problem under the framework of competitive analysis. The major contribution of this paper is the development of a unified approach that achieves the best-possible competitive ratios for setups with different supply costs. Specifically, we show that when there is no supply cost or the supply cost function is linear, our model is essentially a standard 0-1 knapsack problem, for which our approach achieves logarithmic competitive ratios that match the state-of-the-art (which is optimal). For the more challenging setup when the supply cost is strictly-convex, we provide online mechanisms, for the first time, that lead to the optimal competitive ratios as well. To the best of our knowledge, this is the first approach that unifies the characterization of optimal competitive ratios in online resource allocation for different setups including zero, linear and strictly-convex supply costs.

# Summary. An optional shortened abstract.
summary: This paper proposes an approach that unifies the design of online mechanisms for resource allocation with arbitrary strictly-convex supply cost functions and stringent capacity limits.

# tags:
# - Source Themes
featured: true

#links:
# - name: "Conference Version in ACM Sigmetrics"
#   url: "http://arxiv.org/pdf/1512.04133v1"
url_pdf: 
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
  caption:
  focal_point: ""
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ["network_resource_allocation"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
