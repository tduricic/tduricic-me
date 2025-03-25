---
title: "Exploiting weak ties in trust-based recommender systems using regular equivalence"
authors:
- admin
- Emanuel Lacić
- Dominik Kowald
- Elisabeth Lex
author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2019-06-12T00:00:00Z"
doi: "10.1145/3298689.334698"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-06-12T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: '*	Presented as a Spotlight Talk at the "European Symposium Series on Societal Challenges in Computational Social Science - Polarization and Radicalization"*'
publication_short: "EURO CSS'19"

abstract: User-based Collaborative Filtering (CF) is one of the most popular approaches to create recommender systems. CF, however, suffers from data sparsity and the cold-start problem since users often rate only a small fraction of available items. One solution is to incorporate additional information into the recommendation process such as explicit trust scores that are assigned by users to others or implicit trust relationships that result from social connections between users. Such relationships typically form a very sparse trust network, which can be utilized to generate recommendations for users based on people they trust. In our work, we explore the use of regular equivalence applied to a trust network to generate a similarity matrix that is used for selecting k-nearest neighbors used for item recommendation. Two vertices in a network are regularly equivalent if their neighbors are themselves equivalent and by using the iterative approach of calculating regular equivalence, we can study the impact of strong and weak ties on item recommendation. We evaluate our approach on cold-start users on a dataset crawled from Epinions and find that by using weak ties in addition to strong ties, we can improve the performance of a trust-based recommender in terms of recommendation accuracy.

# Summary. An optional shortened abstract.
summary: This study explores using regular equivalence in trust networks to improve Collaborative Filtering recommendations, particularly for cold-start users. While traditional CF suffers from data sparsity when users rate few items, incorporating trust relationships (explicit or implicit) can enhance recommendations. The research applies an iterative regular equivalence calculation to generate similarity matrices for neighbor selection, examining how both strong and weak network ties affect recommendation quality. Evaluations on Epinions data demonstrate that incorporating weak ties alongside strong ties significantly improves recommendation accuracy for cold-start users in trust-based recommender systems.

tags:
- Recommender Systems
- Trust Networks
- Weak Ties
- Network Theory
- Regular Equivalence
- Collaborative Filtering
- Machine Learning
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/1907.11620
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
  caption: "Comparison of recommendation algorithms using strong ties (direct trust connections) vs. weak ties (indirect connections), showing that incorporating weak ties (KSPCMB) improves recommendation accuracy over baseline methods."
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

