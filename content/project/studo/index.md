---
title: "Studo/Talto Job Matchmaking Platform"
summary: "Developed and deployed a personalized job matchmaking recommender system for Studo, later spun off into the standalone platform Talto, significantly enhancing student engagement and job application rates."
tags:
  - Recommender Systems
  - Matchmaking
  - Machine Learning
  - Real-Time Recommendations
  - Data Pipeline
  - Vector Search
  - Project Management
  - User Modeling
  - Embeddings
date: '2017-06-01T00:00:00Z'

external_link: ''

image:
  caption: 'Studo Job Matchmaking Platform'
  focal_point: Smart

links: []

url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

slides: ""
---

## Project Overview _(June 2017 – September 2019)_

At Know Center Research, we partnered with Studo, a widely-used student app in Germany and Austria, to develop a personalized recommender system for their job listings feature. The successful solution later evolved into the dedicated platform "Talto – Talents of Tomorrow," significantly enhancing the student job application process through intelligent matchmaking.

The initial project phase ("Studo Matchmaking Recommender – Empfehlungs Plattform personalisierter Job Anzeigen für Studenten") ran from June 2017 to May 2018. Following its success, we secured additional funding from the Austrian Research Promotion Agency (FFG) for the follow-up project ("FAT – Fair, Accountable & Transparent Matchmaking: Explainability, Sessions, Scoring and Biases for Passive Sourcing"), which took place from October 2018 to September 2019.

## Technical Challenges

- Defining meaningful and varied recommender use-cases for student-job matchmaking
- Developing custom real-time recommender algorithms to handle diverse data and contexts
- Ensuring scalability and seamless integration into the Studo app infrastructure
- Addressing fairness, transparency, and explainability in recommendations

## Technologies & Methods

- **Core Development:** Java, Apache Solr, Microservices with ScaR recommender framework
- **Machine Learning & Algorithms:** Python, Doc2Vec embeddings, Autoencoders, Vector Search
- **Deployment & Testing:** Docker, Continuous Integration, Extensive Testing
- **Research & Documentation:** Scientific publication writing, comprehensive documentation

## Results & Impact

- Improved user engagement with the Studo job marketplace (~20% increase)
- Increased application rate to job postings (~18% increase)
- Conducted pioneering research on matchmaking algorithms tailored for student and graduate job markets
- Enabled high-quality personalization even for anonymous users and additional content recommendations (e.g., news articles)
- Produced multiple impactful academic publications
- Featured as an FFG success story ([full story here](https://www.ffg.at/sites/default/files/allgemeine_downloads/strukturprogramme/20180329_know_successstory_en_moshbit.pdf))

### Selected Publications

```bibtex
@article{lacic2017beyond,
  title={Beyond accuracy optimization: On the value of item embeddings for student job recommendations},
  author={Lacic, Emanuel and Kowald, Dominik and Reiter-Haas, Markus and Slawicek, Valentin and Lex, Elisabeth},
  journal={arXiv preprint arXiv:1711.07762},
  year={2017}
}

@inproceedings{reiter2017studo,
  title={Studo Jobs: Enriching Data With Predicted Job Labels},
  author={Reiter-Haas, Markus and Slawicek, Valentin and Lacic, Emanuel},
  booktitle={CEUR Workshop Proceedings},
  volume={2025},
  year={2017},
  organization={RWTH Aachen}
}

@inproceedings{lacic2019should,
  title={Should we embed? A study on the online performance of utilizing embeddings for real-time job recommendations},
  author={Lacic, Emanuel and Reiter-Haas, Markus and Duricic, Tomislav and Slawicek, Valentin and Lex, Elisabeth},
  booktitle={Proceedings of the 13th ACM conference on recommender systems},
  pages={496--500},
  year={2019}
}

@article{lacic2020using,
  title={Using autoencoders for session-based job recommendations},
  author={Lacic, Emanuel and Reiter-Haas, Markus and Kowald, Dominik and Reddy Dareddy, Manoj and Cho, Junghoo and Lex, Elisabeth},
  journal={User Modeling and User-Adapted Interaction},
  volume={30},
  pages={617--658},
  year={2020},
  publisher={Springer}
}

@inproceedings{reiter2020heterogeneous,
  title={On the heterogeneous information needs in the job domain: A unified platform for student career},
  author={Reiter-Haas, Markus and Wittenbrink, David and Lacic, Emanuel},
  booktitle={Proceedings of the 14th ACM Conference on Recommender Systems},
  pages={573--574},
  year={2020}
}
```

## Personal Contribution

- Managed a team of five, overseeing project execution, requirements engineering, and budget planning
- Actively contributed as a Software Engineer, ML Engineer, and Data Scientist to the development and implementation of recommender algorithms
- Coordinated deployment and continuous improvement of the platform
- Authored academic publications and secured additional project funding from FFG
- Co-advised academic work including one Master's thesis and supported the onboarding of one PhD student
