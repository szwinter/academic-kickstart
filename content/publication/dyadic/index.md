---
title: "Fixed-Horizon Temporal Difference Methods for Stable Reinforcement Learning"
authors:
- Kris de Asis
- admin
- Silviu Pitis
- Richard S. Sutton
- Daniel Graves
date: "2020-02-07"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-02-07"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In AAAI 2020
publication_short: In AAAI 2020

abstract: We explore fixed-horizon temporal difference (TD) methods, reinforcement learning algorithms for a new kind of value function that predicts the sum of rewards over a fixed number of future time steps. To learn the value function for horizon h, these algorithms bootstrap from the value function for horizon h−1, or some shorter horizon. Because no value function bootstraps from itself, fixed-horizon methods are immune to the stability problems that plague other off-policy TD methods using function approximation (also known as "the deadly triad"). Although fixed-horizon methods require the storage of additional value functions, this gives the agent additional predictive power, while the added complexity can be substantially reduced via parallel updates, shared weights, and n-step bootstrapping. We show how to use fixed-horizon value functions to solve reinforcement learning problems competitively with methods such as Q-learning that learn conventional value functions. We also prove convergence of fixed-horizon temporal difference methods with linear and general function approximation. Taken together, our results establish fixed-horizon TD methods as a viable new way of avoiding the stability problems of the deadly triad. 

tags:
- Source Themes
featured: true

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/abs/1909.03906
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Learning curve of FH Q-learning vs. DQN'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->
