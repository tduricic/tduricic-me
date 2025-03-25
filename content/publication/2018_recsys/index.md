---
title: "Trust-based collaborative filtering: tackling the cold start problem using regular equivalence"
authors:
- admin
- Emanuel Lacić
- Dominik Kowald
- Elisabeth Lex
author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2018-09-27T00:00:00Z"
doi: "10.1145/3240323.3240404"

# Schedule page publish date (NOT publication's date).
publishDate: "2018-09-27T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*Proceedings of the 12th ACM Conference on Recommender Systems*"
publication_short: "RecSys'18"

abstract: User-based Collaborative Filtering (CF) is one of the most popular approaches to create recommender systems. This approach is based on finding the most relevant k users from whose rating history we can extract items to recommend. CF, however, suffers from data sparsity and the cold-start problem since users often rate only a small fraction of available items. One solution is to incorporate additional information into the recommendation process such as explicit trust scores that are assigned by users to others or implicit trust relationships that result from social connections between users. Such relationships typically form a very sparse trust network, which can be utilized to generate recommendations for users based on people they trust. In our work, we explore the use of regular equivalence applied to a trust network to generate a similarity matrix that is used to select the k-nearest neighbors for recommending items. We evaluate our approach on Epinions and we find that we can outperform related methods for tackling cold-start users in terms of recommendation accuracy.

# Summary. An optional shortened abstract.
summary: This study uses regular equivalence in trust networks to improve recommendations for cold-start users in Collaborative Filtering systems. By applying this network science measure to user trust relationships, the researchers create a similarity matrix that helps select better user neighbors for recommendation purposes. Testing on the Epinions dataset shows their approach outperforms related methods in recommendation accuracy for new users with few ratings.

tags:
- Recommender Systems
- Trust Networks
- Cold-Start Problem
- Collaborative Filtering
- Regular Equivalence
- Network Analysis
- Machine Learning
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/1807.06839
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
  caption: "Comparison of recommendation accuracy showing our KSPCMB approach outperforms baseline methods and other KS-based algorithms for cold-start users on the Epinions dataset, with Recall-Precision metrics for various recommendation list sizes."
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

