+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 24  # Order that this section will appear.

title = "Primary Research"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  color = "white"
  
  # Text color (true=light or false=dark).
  text_color_light = false

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

It is often difficult to specify a realistic likelihood for real-world data. Generalized Bayesian methods replace the negative log-likelihood with a loss function, defining a computationally tractable pseudo-posterior that can be used in place of the original posterior. Unfortunately, generalized posteriors may be seriously miscalibrated, resulting in dramatic over/underrepresentation of uncertainty. We are extending generalized posteriors to a larger class of distributions which can be accurately calibrated in a wide array of applications, including those with manifold-valued parameters. Motivating problems include principal component regression, multi-scale time series analysis, and hierarchical clustering.
