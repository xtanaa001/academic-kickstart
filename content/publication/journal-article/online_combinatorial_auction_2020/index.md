---
title: "Online Combinatorial Auction for Resource Allocation with Supply Costs and Capacity Limits"
authors:
 - "**Xiaoqi Tan**"
 - Alberto Leon-Garcia
 - Yuan Wu
 - Danny H.K. Tsang
date: "2019-11-17T00:00:00Z"
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
summary: We study the mechanism design for online allocation of resources. A single supplier who allocates capacity-limited resources (e.g., computing cycles, network bandwidth, energy, etc. ) to requests that arrive in a sequential and arbitrary manner.

# tags:
# - Source Themes
featured: true


links:
  -  icon: ieee
     icon_pack: ai
     name: IEEE Xplore
     url: "http://arxiv.org/pdf/1512.04133v1"
  - icon: arxiv
    icon_pack: ai
    name: arXiv Report
    url: "http://arxiv.org/pdf/1512.04133v1"

url_pdf: http://arxiv.org/pdf/1512.04133v1
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
projects: ["network_resource_allocation"]

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

### Major Results of This Paper
The major contribution of this paper is the design of a general posted-price mechanism for online combinatorial auction problems. 

\begin{align}
\phi'(x) =
\begin{cases} \alpha\cdot \frac{\phi(x) - f(x)}{f^{-1}(\phi(x))} & \text{if } x\in [0,u], \\\\\\
\alpha(\phi(x) - f(x)) & \text{if } x\in [u,1]. \end{cases} 
\end{align}

{{< figure src="https://raw.githubusercontent.com/gcushen/hugo-academic/master/academic.png" title="Academic is mobile first with a responsive design to ensure that your site looks stunning on every device." >}}