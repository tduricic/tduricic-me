---
title: "Should We Embed in Chemistry? A Comparison of Unsupervised Transfer Learning with PCA, UMAP, and VAE on Molecular Fingerprints"
authors:
- Mario Lovrić
- admin
- Han T.N. Tran
- Hussain Hussain
- Emanuel Lacić
- Morten A. Rasmussen
- Roman Kern
author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2021-07-22T00:00:00Z"
doi: "10.3390/ph14080758"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-07-22T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Pharmaceuticals (MDPI)*"
publication_short: "Pharmaceuticals (MDPI)"

abstract: Methods for dimensionality reduction are showing significant contributions to knowledge generation in high-dimensional modeling scenarios throughout many disciplines. By achieving a lower dimensional representation (also called embedding), fewer computing resources are needed in downstream machine learning tasks, thus leading to a faster training time, lower complexity, and statistical flexibility. In this work, we investigate the utility of three prominent unsupervised embedding techniques (principal component analysis—PCA, uniform manifold approximation and projection—UMAP, and variational autoencoders—VAEs) for solving classification tasks in the domain of toxicology. To this end, we compare these embedding techniques against a set of molecular fingerprint-based models that do not utilize additional pre-preprocessing of features. Inspired by the success of transfer learning in several fields, we further study the performance of embedders when trained on an external dataset of chemical compounds. To gain a better understanding of their characteristics, we evaluate the embedders with different embedding dimensionalities, and with different sizes of the external dataset. Our findings show that the recently popularized UMAP approach can be utilized alongside known techniques such as PCA and VAE as a pre-compression technique in the toxicology domain. Nevertheless, the generative model of VAE shows an advantage in pre-compressing the data with respect to classification accuracy.

# Summary. An optional shortened abstract.
summary: This study examines three unsupervised dimensionality reduction techniques (PCA, UMAP, and VAEs) for toxicology classification tasks. The research compares these embedding methods against standard molecular fingerprint models and explores transfer learning by training embedders on external chemical compound datasets. By testing various embedding dimensions and external dataset sizes, the findings demonstrate that UMAP can effectively complement established techniques like PCA and VAE for pre-compression in toxicology. However, VAE's generative approach shows superior performance in pre-compression for classification accuracy.


tags:
- Transfer Learning
- Dimensionality Reduction
- Molecular Fingerprints
- Variational Autoencoders
- UMAP
- Chemical Informatics
- Machine Learning
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.mdpi.com/1424-8247/14/8/758/pdf?version=1628069072
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
  caption: 'Performance comparison of different dimensionality reduction techniques (fingerprint baseline, PCA, UMAP, and VAE) for toxicology classification, showing average accuracy with error bars across multiple classifier runs.'
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

