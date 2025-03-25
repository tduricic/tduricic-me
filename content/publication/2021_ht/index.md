---
title: "Structack: Structure-based Adversarial Attacks on Graph Neural Networks"
authors:
- Hussain Hussain
- admin
- Elisabeth Lex
- Denis Helić
- Markus Strohmaier
- Roman Kern
author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2021-08-29T00:00:00Z"
doi: "10.1145/3465336.3475110"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-08-29T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*Proceedings of the 32nd ACM Conference on Hypertext and Social Media*"
publication_short: "HT'21"

abstract: Recent work has shown that graph neural networks (GNNs) are vulnerable to adversarial attacks on graph data. Common attack approaches are typically informed, i.e. they have access to information about node attributes such as labels and feature vectors. In this work, we study adversarial attacks that are uninformed, where an attacker only has access to the graph structure, but no information about node attributes. Here the attacker aims to exploit structural knowledge and assumptions, which GNN models make about graph data. In particular, literature has shown that structural node centrality and similarity have a strong influence on learning with GNNs. Therefore, we study the impact of centrality and similarity on adversarial attacks on GNNs. We demonstrate that attackers can exploit this information to decrease the performance of GNNs by focusing on injecting links between nodes of low similarity and, surprisingly, low centrality. We show that structure-based uninformed attacks can approach the performance of informed attacks, while being computationally more efficient. With our paper, we present a new attack strategy on GNNs that we refer to as Structack. Structack can successfully manipulate the performance of GNNs with very limited information while operating under tight computational constraints. Our work contributes towards building more robust machine learning approaches on graphs.

# Summary. An optional shortened abstract.
summary: Graph neural networks (GNNs) are vulnerable to adversarial attacks, but most attack methods require node attribute information. This paper introduces Structack, an uninformed attack strategy that exploits only graph structural properties without needing node attributes. By targeting links between nodes with low similarity and low centrality, Structack approaches the effectiveness of informed attacks while being computationally more efficient. The findings demonstrate that structural knowledge alone can significantly degrade GNN performance, contributing to the development of more robust graph-based machine learning methods.


tags:
- Graph Neural Networks
- Adversarial Attacks
- Network Security
- Node Centrality
- Graph Structure
- Robustness
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://dl.acm.org/doi/pdf/10.1145/3465336.3475110
#url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_dataset: ''
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: ''
#url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: "Comparison of GNN classification attack strategies: (a) standard GNN, (b) informed attack with full node information, (c) naive uninformed attack using only graph structure, and (d) Structack's more effective uninformed attack targeting low centrality/similarity nodes."
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

