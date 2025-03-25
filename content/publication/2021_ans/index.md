---
title: "The interplay between communities and homophily in semi-supervised classification using graph neural networks"
authors:
- Hussain Hussain
- admin
- Elisabeth Lex
- Denis Helić
- Roman Kern
author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2021-10-26T00:00:00Z"
doi: "10.1007/s41109-021-00423-1"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-10-26T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Applied Network Science*"
publication_short: "Appl. Netw. Sci"

abstract: Graph Neural Networks (GNNs) are effective in many applications. Still, there is a limited understanding of the effect of common graph structures on the learning process of GNNs. To fill this gap, we study the impact of community structure and homophily on the performance of GNNs in semi-supervised node classification on graphs. Our methodology consists of systematically manipulating the structure of eight datasets, and measuring the performance of GNNs on the original graphs and the change in performance in the presence and the absence of community structure and/or homophily. Our results show the major impact of both homophily and communities on the classification accuracy of GNNs, and provide insights on their interplay. In particular, by analyzing community structure and its correlation with node labels, we are able to make informed predictions on the suitability of GNNs for classification on a given graph. Using an information-theoretic metric for community-label correlation, we devise a guideline for model selection based on graph structure. With our work, we provide insights on the abilities of GNNs and the impact of common network phenomena on their performance. Our work improves model selection for node classification in semi-supervised settings.




# Summary. An optional shortened abstract.
summary: This study investigates how community structure and homophily influence Graph Neural Networks (GNNs) in semi-supervised node classification tasks. By systematically modifying eight datasets and measuring GNN performance with and without these structural properties, we demonstrate their significant impact on classification accuracy and reveal insights about their interaction. We introduce an information-theoretic metric to quantify community-label correlation, providing practical guidelines for model selection based on graph structure. Our findings enhance understanding of GNN capabilities and improve model selection for semi-supervised node classification tasks.


tags:
- Graph Neural Networks
- Community Structure
- Homophily
- Semi-Supervised Learning
- Node Classification
- Network Science
- Machine Learning
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://link.springer.com/content/pdf/10.1007/s41109-021-00423-1.pdf
#url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_dataset: ''
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: ''
#url_video: 'https://www.youtube.com/watch?v=iFdK_TUcVQs'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'GNN performance across homophilic datasets showing how accuracy varies with changes in community structure and homophily levels.'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [ddai]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example

# {{% callout note %}}
# Click the *Cite* button above to demo the feature to enable visitors to import publication metadata # into their reference management software.
# {{% /callout %}}
#
# {{% callout note %}}
# Create your slides in Markdown - click the *Slides* button to check out the example.
# {{% /callout %}}
# 
# Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
---

