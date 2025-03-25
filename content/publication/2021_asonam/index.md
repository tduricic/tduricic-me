---
title: "My friends also prefer diverse music: homophily and link prediction with user preferences for mainstream, novelty, and diversity in music"
authors:
- admin
- Dominik Kowald
- Markus Schedl
- Elisabeth Lex
author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2022-01-19T00:00:00Z"
doi: "10.1145/3487351.3492706"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-19T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*Proceedings of the 2021 IEEE/ACM International Conference on Advances in Social Networks Analysis and Mining*"
publication_short: "ASONAM'21"

abstract: Homophily describes the phenomenon that similarity breeds connection, i.e., individuals tend to form ties with other people who are similar to themselves in some aspect(s). The similarity in music taste can undoubtedly influence who we make friends with and shape our social circles. In this paper, we study homophily in an online music platform Last.fm regarding user preferences towards listening to mainstream (M), novel (N), or diverse (D) content. Furthermore, we draw comparisons with homophily based on listening profiles derived from artists users have listened to in the past, i.e., artist profiles. Finally, we explore the utility of users' artist profiles as well as features describing M, N, and D for the task of link prediction. Our study reveals that - (i) users with a friendship connection share similar music taste based on their artist profiles; (ii) on average, a measure of how diverse is the music two users listen to is a stronger predictor of friendship than measures of their preferences towards mainstream or novel content, i.e., homophily is stronger for D than for M and N; (iii) some user groups such as high-novelty-seekers (explorers) exhibit strong homophily, but lower than average artist profile similarity; (iv) using M, N and D achieves comparable results on link prediction accuracy compared with using artist profiles, but the combination of features yields the best accuracy results, and (v) using combined features does not add value if graph-based features such as common neighbors are available, making M, N, and D features primarily useful in a cold-start user recommendation setting for users with few friendship connections. The insights from this study will inform future work on social context-aware music recommendation, user modeling, and link prediction.

# Summary. An optional shortened abstract.
summary: This study examines homophily on Last.fm based on users' preferences for mainstream, novel, or diverse music content. We compare friendship connections to listening profiles and evaluate these features for link prediction. Results show that friends share similar artist preferences, with diversity being a stronger predictor of friendship than mainstream or novelty preferences. While high-novelty users show strong homophily, they have lower artist profile similarity. Mainstream/novel/diverse features perform comparably to artist profiles in link prediction, with combined features yielding best results—though adding no value when graph-based features are available. These insights inform music recommendation, user modeling, and cold-start link prediction.


tags:
- Homophily
- Link Prediction
- Music Recommendations
- User Preferences
- Diversity
- Social Networks
- Novelty
- Machine Learning
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://dl.acm.org/doi/pdf/10.1145/3487351.3492706
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
  caption: 'O/E edge ratios and artist similarity patterns between user groups based on mainstream, novelty, and diversity preferences in original and randomized networks.'
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

