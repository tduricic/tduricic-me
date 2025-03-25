---
title: "PyChemFlow: an automated pre-processing pipeline in Python for reproducible machine learning on chemical data"
authors:
- Mario Lovrić
- admin
- Hussain Hussain
- Bono Lucić
- Roman Kern
author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2023-07-20T00:00:00Z"
doi: "10.26434/chemrxiv-2023-3zpw0"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-07-20T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "*ChemRxiv*"
publication_short: "ChemRxiv"

abstract: PyChemFlow is a Python library for automated and reproducible data pre-processing. Based on open-source code, PyChemFlow has simple requirements that rely on pandas, scikit-learn and joblib. The library's backbone is built up of transformer objects, which are fully constructed during the PyChemFlow fitting process using training data and can be conveniently stored using joblib. The user can run the library with a one-line command after splitting data into train and validation sets or while working with additional data. This is especially useful when reproducibility is critical. PyChemFlow also offers the ability to persistently store metadata, in addition to providing customizable and configurable data manipulation steps.



# Summary. An optional shortened abstract.
summary: PyChemFlow is a Python library for automated, reproducible data pre-processing that leverages transformer objects built on minimal dependencies. It enables one-line execution with train-validation splits, persistent storage of transformers and metadata, and customizable data manipulation steps, making it ideal for applications requiring strict reproducibility.

tags:
- Data Preprocessing
- Chemical Informatics
- Reproducibility
- Pipeline Automation
- Scientific Computing
- Python Libraries
- Machine Learning
- Data Pipeline
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://chemrxiv.org/engage/api-gateway/chemrxiv/assets/orp/resource/item/64b9082aae3d1a7b0d0a53dc/original/py-chem-flow-an-automated-pre-processing-pipeline-in-python-for-reproducible-machine-learning-on-chemical-data.pdf
#url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_dataset: ''
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'A schematics representation of the transformer object.'
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

