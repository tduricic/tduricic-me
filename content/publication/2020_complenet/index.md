---
title: "On the Impact of Communities on Semi-supervised Classification Using Graph Neural Networks"
authors:
- Hussain Hussain
- admin
- Elisabeth Lex
- Roman Kern
- Denis Helić
author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2021-01-05T00:00:00Z"
doi: "10.1007/978-3-030-65351-4_2"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-01-05T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*Proceedings of the Ninth International Conference on Complex Networks and Their Applications COMPLEX NETWORKS 2020*"
publication_short: "CompleNet'20"

abstract: Graph Neural Networks (GNNs) are effective in many applications. Still, there is a limited understanding of the effect of common graph structures on the learning process of GNNs. In this work, we systematically study the impact of community structure on the performance of GNNs in semi-supervised node classification on graphs. Following an ablation study on six datasets, we measure the performance of GNNs on the original graphs, and the change in performance in the presence and the absence of community structure. Our results suggest that communities typically have a major impact on the learning process and classification performance. For example, in cases where the majority of nodes from one community share a single classification label, breaking up community structure results in a significant performance drop. On the other hand, for cases where labels show low correlation with communities, we find that the graph structure is rather irrelevant to the learning process, and a feature-only baseline becomes hard to beat. With our work, we provide deeper insights in the abilities and limitations of GNNs, including a set of general guidelines for model selection based on the graph structure.

# Summary. An optional shortened abstract.
summary: This study examines how community structures in graphs affect Graph Neural Networks (GNNs) in node classification tasks. Through experiments on six datasets, researchers found that community structures significantly impact GNN performance. When nodes in a community mostly share the same label, disrupting the community structure dramatically reduces performance. Conversely, when labels don't correlate with communities, graph structure becomes less relevant and simple feature-based models perform comparably. The research provides insights and guidelines for selecting appropriate models based on graph structure characteristics.

tags:
- Graph Neural Networks
- Community Detection
- Semi-Supervised Learning
- Node Classification
- Community Structure
- Network Analysis
- Machine Learning
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/2010.16245
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
  caption: 'Graph comparing GNN accuracy across original and modified networks, showing community structures help performance on citation graphs but hinder results on WebKB, with correlation to uncertainty coefficients.'
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

