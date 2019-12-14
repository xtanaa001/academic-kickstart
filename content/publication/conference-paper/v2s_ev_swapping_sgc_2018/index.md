---
title: Online Price-based Vehicle-to-Station Recommendations for EV Battery Swapping
authors:
 - Liang Ni
 - Bo Sun
 - "**Xiaoqi Tan**"
 - Danny H.K. Tsang
date: "2018-10-10T00:00:00Z"
# doi: ""

tags: 
  - Smart Grid

# Schedule page publish date (NOT publication's date).
#publishDate: "2019-11-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2018 IEEE International Conference on Smart Grid Communications (SmartGridComm)"
publication_short: ""

abstract: We present a framework to integrate the choice of electric vehicle (EV) customers into the vehicle-to-station (V2S) routing problem for battery swapping. Instead of assigning stations to each EV customer directly, we provide a recommendation, including a list of station-price pairs that are available for EV battery swapping services, for customers to choose. Compared with assignment, recommendation is closer to reality for scenarios lacking incentives for the cooperation of customers such as the battery swapping services of private EVs. In this paper, we model customers' behavior by their choice probability given a particular recommendation, which can be readily obtained based on analytics techniques once the real data are available. We propose an online V2S recommendation algorithm, which aims at maximizing the expected revenue of a group of battery swapping stations (BSSs) and ensuring the quality service of EV customers. Leveraging the primal-dual analysis, we show that the loss of revenue due to online EV arrivals is theoretically bounded by a provable competitive ratio. Moreover, numerical tests also validate that the proposed online algorithm can significantly outperform benchmarks in maximizing revenues in online settings.

# Summary. An optional shortened abstract.
# summary: This paper concerns the mechanism design for online resource allocation in a strategic setting. In this setting, a single supplier allocates capacity-limited resources to requests that arrive in a sequential and arbitrary manner. Each request is associated with an agent who may act selfishly to misreport the requirement and valuation of her request.

# tags:
# - Source Themes
featured: false

links:
 - icon: ieee
   icon_pack: ai
   name: "IEEE Xplore "
   url: "https://ieeexplore.ieee.org/document/8587503"
   
url_pdf: https://www.sigmetrics.org/mama/abstracts/Tan.pdf
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
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---