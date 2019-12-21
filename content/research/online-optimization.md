+++
# A Recent Publications section created with the Pages widget.
# This section displays recent blog posts from `content/publication/`.

widget = "pages"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 25  # Order that this section will appear.

title = "Online Optimization"
# subtitle = "Online Algorithms, Mechanism Design and Machine Learning"



[content]
  # Page type to display. E.g. post, talk, or publication.
  page_type = "publication"
  
  # Choose how much pages you would like to display (0 = all pages)
  count = 2
  
  # Choose how many pages you would like to offset by
  offset = 0

  # Page order. Descending (desc) or ascending (asc) date.
  order = "desc"

  # Filter posts by a taxonomy term.
  [content.filters]
    tag = "incentives"
    category = ""
    publication_type = ""
    exclude_featured = false
  
  
[design]
  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  view = 4
  
[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.
    
  # Background color.
  # color = "white"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  # image = "background.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true  
  
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
 
# {{% alert note %}} 
# Quickly discover relevant content by [filtering publications]({{< ref "/publication/_index.md" >}}).
# {{% /alert %}}

# ## Online Optimization
# Reinforcement learning is concerned about making sequential decisions under uncertainty based on the theory of Markov Decision Process. For 

# {{< figure library="true" src="competitive_ratio.png" title="Achieveable regions of competitive ratios of the proposed online algorithm under three cases" lightbox="true" >}}

# ## Recent Publications
+++


I study incentive-aware decision making based on online algorithms, mechanism design and machine learning. In particular, I focus on designing sequential decision making algorithms when there is no complete information of future. Moreover, such sequential decision making problems can be substaintially challenged if there exist multiple agents with self-interested behaviors. 

###  Online Combinatorial Optimization
Mechanism design is concerned about designing a protocol that can implement a game. Online mechanism design sits at the intersection between mechanism design and online algorithm, where decisions must be made in an online fashion with incomplete future information. Posted-Price Mechanisms. 

$$
	\text{maximize}  \sum_{n=1}^N v_n x_n - \sum_{t=1}^T f\left(\sum_{n=1}^N r_n^tx_n\right),
	\text{subject to} \sum_{n=1}^N r_n^tx_n\leq 1, \forall  t\in\mathcal{T},
	x_n = \{0,1\},\forall n\in\mathcal{N}.
$$

### Online Convex Optimization
Mechanism design is concerned about designing a protocol that can implement a game. Online mechanism design sits at the intersection between mechanism design and online algorithm, where decisions must be made in an online fashion with incomplete future information.

## Recent Publications