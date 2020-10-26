---
title: "Multi-scale graph principal component analysis for connectomics"
authors:
- admin
- Zhengwu Zhang
- David Dunson
date: "2020-05-20"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-05-20"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
# publication: place
# publication_short: place

abstract: In brain connectomics, the cortical surface is parcellated into different regions of interest (ROIs) prior to statistical analysis.  The brain connectome for each individual can then be represented as a graph, with the nodes corresponding to ROIs and edges to connections between ROIs.  Such a graph can be summarized as an adjacency matrix, with each cell containing the strength of connection between a pair of ROIs. These matrices are symmetric with the diagonal elements corresponding to self-connections typically excluded.  A major disadvantage of such representations of the connectome is their sensitivity to the chosen ROIs, including critically the number of ROIs and hence the scale of the graph.  As the scale becomes finer and more ROIs are used, graphs become increasingly sparse.  Clearly, the results of downstream statistical analyses can be highly dependent on the chosen parcellation.  To solve this problem, we propose a multi-scale graph factorization, which links together scale-specific factorizations through a common set of individual-specific scores.  These scores summarize an individual's brain structure combining information across measurement scales.  We obtain a simple and efficient algorithm for implementation, and illustrate substantial advantages over single scale approaches in simulations and analyses of the Human Connectome Project dataset.  

tags:
- Source Themes
featured: true

links: https://arxiv.org/abs/2010.02332
# - name: Custom Link
#   url: http://example.org
# url_pdf: https://arxiv.org/abs/1909.03906
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
  caption: 'caption'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

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
