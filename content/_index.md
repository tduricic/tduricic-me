---
# Leave the homepage title empty to use the site title
title: Tomislav Đuričić | Personal Website
date: 2024-09-15
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text: 
  - block: features
    content:
      title: Skills
      items:
        - name: Research & Problem-solving
          description: Research design, experimental methodology, data interpretation, and statistical analysis. Grant proposal writing, project management, and funding acquisition. Literature synthesis, critical evaluation, and identification of research gaps. Scientific writing and presentation for academic conferences and industry audiences. Interdisciplinary collaboration across academic and industry settings. Translating complex research findings into practical applications.
          icon: chart-line
          icon_pack: fas
        - name: ML & Data Science
          description: Deep learning with PyTorch and graph neural networks (PyG). LLM integration, evaluation, and fine-tuning for industrial applications. Recommendation systems design and evaluation (Scikit-surprise, Elliot, ScaR). Natural language processing with transformers and embeddings. Data manipulation and visualization (Pandas, NumPy, Matplotlib, Seaborn). Time-series forecasting, anomaly detection, and dimensionality reduction. User behavior modeling and network analysis (NetworkX).
          icon: robot
          icon_pack: fas
        - name: Software Engineering
          description: Python and Java development with object-oriented design patterns. AR/VR development with Unity for industrial digital twins and immersive analytics. Microservices architecture and RESTful API design. Database systems (SQL, NoSQL) including PostgreSQL, Apache Solr, and MongoDB. Web application development with Spring Boot and related frameworks. Containerization with Docker and deployment on cloud platforms (AWS, GCP). CI/CD pipelines and version control with Git.
          icon: code
          icon_pack: fas
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Senior Machine Learning Researcher
          company: Know Center Research
          company_url: 'https://www.know-center.at/'
          company_logo: org-kc
          location: Graz, Austria
          date_start: '2024-01-01'
          date_end: ''
          description: |2-
              Conducting advanced research in:

              * Immersive analytics and AI assistants for industrial digital twins
              * Graph neural networks with focus on beyond-accuracy metrics
              * Large language model integration in AR/VR environments
              * Contributing to scientific publications and research proposals
        - title: University Assistant (PhD Researcher)
          company: Graz University of Technology
          company_url: 'https://www.tugraz.at/home'
          company_logo: org-tug
          location: Graz, Austria
          date_start: '2018-10-01'
          date_end: '2023-12-31'
          description: |2-
              Conducted doctoral research and academic activities including:

              * Research on graph neural networks, recommender systems, and user behavior
              * Contributing to successful research proposals worth over €600,000
              * Co-advising bachelor and master thesis students in ML and data science
              * Teaching courses and leading lab exercises in data science topics
              * Automotive diagnostic systems utilizing sequential recommendation (AVL Research Project)
              * Publishing in top-tier conferences (RecSys, ASONAM, HT) and journals
              * Presenting research at international conferences and workshops
        - title: Project Manager & ML Engineer
          company: Know Center Research
          company_url: 'https://www.know-center.at/'
          company_logo: org-kc
          location: Graz, Austria
          date_start: '2017-06-01'
          date_end: '2023-12-31'
          description: |2-
              Led strategic projects while advancing technical implementation:
              
              * Project manager for the Studo/Talto job matchmaking project (2017-2019, team of 5)
              * Project manager for the COGSTEPS ERASMUS+ project (2020-2023)
              * Project manager for the VHDD platform development (2018-2019)
              * Securing €150,000 FFG funding for the Studo project follow-up ("FAT")
              * Designing and implementing recommender systems across multiple domains
              * Authoring scientific publications on recommender systems and ML applications
              * Bridging academic research and practical industry applications
        - title: Software & ML Engineer / Data Scientist
          company: Know Center Research
          company_url: 'https://www.know-center.at/'
          company_logo: org-kc
          location: Graz, Austria
          date_start: '2016-03-01'
          date_end: '2017-05-31'
          description: |2-
              Developed advanced ML solutions for industry partners:
              
              * Designing real-time data pipelines for retail analytics (Detego Fashion)
              * Creating time-series prediction dashboard for Porsche Holding Salzburg
              * Implementing image analysis systems for photo calendar recommendations
              * Contributing to the ScaR recommender framework development
              * Applying machine learning techniques to various industry problems
              * Transforming research concepts into production-ready systems
        - title: ERASMUS+ internship
          company: Know Center Research
          company_url: 'https://www.know-center.at/'
          company_logo: org-kc
          location: Graz, Austria
          date_start: '2015-03-01'
          date_end: '2015-08-31'
          description: Conducted research on real-time and trust-based recommender systems, culminating in my master's thesis "Real-Time Recommendations Based on Social Trust" supervised by Prof. Dr. Sc. Vedran Podobnik, Assoc.-Prof. Dr. Elisabeth Lex, and Dr. Emanuel Lacić. My research findings and implementation were successfully integrated into the ScaR (Scalable Recommendation-as-a-service) framework, contributing to the organization's recommender system capabilities.

        
        - title: Junior Android Developer
          company: FZI Research Center for Information Technology
          company_url: 'https://www.fzi.de/en/'
          company_logo: org-fzi
          location: Karlsruhe, Germany
          date_start: '2013-01-01'
          date_end: '2013-10-01'
          description: As part of the Erasmus+ student exchange program, I developed a mobile application for real-time student feedback in collaboration with the Informatics Institute and FZI Research Center. This work formed the basis of my Bachelor's thesis "Mobile Live Interest Meter Application," supervised by Prof. Dr. Rudi Studer and Dr. Verónica Rivera Pelayo, providing a digital solution for capturing and analyzing immediate student engagement data.

        
        - title: Student Developer
          company: Ericsson Nikola Tesla d.d.
          company_url: 'https://www.ericsson.hr/'
          company_logo: org-eri
          location: Zagreb, Croatia / Budapest, Hungary
          date_start: '2014-07-01'
          date_end: '2014-09-15'
          description: Selected for Ericsson's competitive Summer Camp internship program, where I integrated a code plagiarism detection toolkit into the company's internal IDE using JavaScript, HTML, CSS, and the Dojo toolkit. The international program spanned 5 weeks across Zagreb and Budapest locations, providing hands-on development experience and insights into enterprise software development in the telecommunications industry.

    design:
      columns: '2'
  - block: collection
    id: publications
    content:
      title: Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: portfolio
    id: projects
    content:
      title: Selected Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Recommender Systems
          tag: Recommender Systems
        - name: Project Management
          tag: Project Management
        - name: Graph Neural Networks
          tag: Graph Neural Networks
        - name: Time-Series Analysis
          tag: Time-Series Analysis
        - name: User Modeling
          tag: User Modeling
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: accomplishments
    id: teaching
    content:
      title: Teaching
      date_format: Jan 2006
      items:
        - title: '[Data Science in Business 2](https://online.uni-graz.at/kfu_online/ee/ui/ca2/app/desktop/#/slc.tm.cp/student/courses/813930?$ctx=design=ca&$scrollTo=toc_overview)'
          date_end: '2025-03-01'
          date_start: '2022-10-01'
          organization: Graz University of Technology and University of Graz
          organization_url: 'https://www.tugraz.at/studium/studienangebot/masterstudien/computational-social-systems'
          description: |
            Lecturer for this graduate-level course in the joint Computational Social Systems Master's program. My responsibilities included:
            
            * Leading practical lab sessions focused on natural language processing techniques
            * Teaching text preprocessing, feature engineering, and modern NLP approaches
            * Introducing students to transformer architectures and their applications
            * Creating and evaluating a final project using financial textual data
            * Providing guidance on Python libraries including NLTK, spaCy, and Hugging Face Transformers
            * Fostering critical thinking and practical problem-solving skills

        - title: Complexity Science
          date_end: '2019-02-01'
          date_start: '2018-10-01'
          organization: Graz University of Technology
          organization_url: 'https://www.tugraz.at/en/studying-and-teaching/degree-and-certificate-programmes/masters-degree-programmes/information-and-computer-engineering/'
          description: |
            Lecturer for this course in the Information and Computer Engineering Master's program, focusing on:
            
            * Advanced topics from "Complexity - A Guided Tour" by Melanie Mitchell
            * Creating and grading student assignments on complexity principles
            * Teaching concepts including fitness landscapes and evolution of cooperation
            * Guiding students through computational models of complex systems
            * Supporting students in developing mathematical and computational understanding of complexity
    design: 
      columns: '2'
  - block: accomplishments
    id: services
    content:
      title: Services
      date_format: Jan 2006
      items:
        - title: Session Chairing, Mentoring, and Workshop Organization
          date_end: '2025-04-01'
          date_start: '2016-03-01'
          organization: ''
          organization_url: ''
          description:  |
            * **Session Chair** for Research Track Session 5 of the 15th ACM Recommender Systems Conference ([RecSys 2021](https://recsys.acm.org/recsys21/session-5/))
            * **Deep Tech Mentor** for [HEICE (Unlocking High Tech Entrepreneurship and Innovation Competences for Deep Tech Talents)](https://graz.elsevierpure.com/en/projects/heice-unlocking-high-tech-entrepreneurship-and-innovation-compete)
            * **Workshop Organizer** for [COGSTEPS "From Customers to Product"](https://cogsteps.com/cogsteps-fourth-live-program-closes-successfully-from-customers-to-product/) in Graz, Austria (May 2023)
            * **Workshop Co-organizer** for [COGSTEPS "From MVP to First Customers"](https://cogsteps.com/cogsteps-third-live-program-closes-successfully-from-mvp-to-first-customers/) in Ljubljana, Slovenia (January-February 2023)
            * **Workshop Co-organizer** for [COGSTEPS "From Researcher to MVP"](https://cogsteps.com/from-researcher-to-mvp-the-second-cogsteps-live-program-successfully-closed/) in Zagreb, Croatia (August-September 2022)
            * **Workshop Co-organizer** for [COGSTEPS "Startup 101 Bootcamp"](https://cogsteps.com/cogsteps-live-program-has-started-with-startup-101-bootcamp/) in Zagreb, Croatia (January 2022)
            * **Mentor** supporting the [Empowering Deep Tech Innovation through Entrepreneurial Excellence (EDIT+) project](https://www.tugraz.at/en/tu-graz/services/news-stories/tu-graz-news/singleview/article/accelerator-programm-fuer-innovatorinnen)
        - title: Program Committee Membership and Reviewing
          date_end: '2025-04-01'
          date_start: '2016-03-01'
          organization: ''
          organization_url: ''
          description:  |
            **Conferences and Workshops:**
            * ACM RecSys (2018, 2021, 2022, 2023)
            * ACM SIGIR (2022, 2023, 2024, 2025)
            * ACM IUI (2022, 2023, 2024, 2025)
            * ACM WebConf (2022, 2023)
            * ACM WSDM (2022)
            * ACM Hypertext (2019, 2020)
            * ACM UMAP (2021, 2022)
            * ECIR (2023)
            * SIAM SDM (2023)
            * MSM Workshop (2019)
            * RS-BDA (2016)
            
            **Journals:**
            * Frontiers in Big Data | Recommender Systems
            * Social Network Analysis and Mining (SNAM)
            * Complexity
            * Information Sciences
    design: 
      columns: '2'
  - block: accomplishments
    id: awards
    content:
      title: Awards & Grants
      date_format: Jan 2006
      items:
        - title: Best Presentation Award
          date_end: ''
          date_start: '2022-09-26'
          organization: Know Center Research and Institute of Interactive Systems and Data Science
          organization_url: 'https://www.tugraz.at/institute/isds/home'
          description: Received the Best Presentation Award at the institute's PhD retreat for my presentation on beyond-accuracy optimization in social-based recommender systems.
          
        - title: Travel Grant - Euro CSS Symposium
          date_end: ''
          date_start: '2019-09-02'
          organization: European Symposium on Societal Challenges in Computational Social Science
          organization_url: 'http://symposium.computationalsocialscience.eu/2019/'
          description: Received a competitive travel grant to attend the European Symposium in Zurich focused on "Polarization and Radicalization," where I presented my research on cross-platform content diffusion.
          
        - title: Travel Grant - Euro CSS Summer School
          date_end: ''
          date_start: '2019-06-01'  # Adjusted date to avoid duplicate dates
          organization: European Summer School in Computational Social Science
          organization_url: 'http://summerschool.computationalsocialscience.eu/2019/'
          description: Awarded a travel grant to participate in the third Summer School on analyzing multimedia data in Berlin, focusing on computer vision, spatial analysis of urban spaces, and multimedia content modeling.
          
        - title: Erasmus+ Traineeship Scholarship
          date_end: '2015-08-31'
          date_start: '2015-02-01'
          organization: Erasmus+ Programme
          organization_url: 'https://erasmus-plus.ec.europa.eu/opportunities/opportunities-for-individuals/students/traineeships-abroad-for-students'
          description: Secured an Erasmus+ traineeship scholarship to complete a 6-month research internship at Know Center Research in Graz, Austria, where I developed my master's thesis on social trust-based recommendations that was later integrated into their production systems.
          
        - title: Erasmus+ Student Exchange Scholarship
          date_end: '2012-08-31'
          date_start: '2011-09-01'
          organization: Erasmus+ Programme
          organization_url: 'https://erasmus-plus.ec.europa.eu/opportunities/opportunities-for-individuals/students/studying-abroad'
          description: Received a full-year Erasmus+ scholarship to study at the prestigious Karlsruhe Institute of Technology in Germany, where I completed specialized coursework in software engineering and mobile application development.
    design: 
      columns: '2'
  - block: accomplishments
    id: theses
    content:
      title: Supervised Theses
      date_format: Jan 2006
      items:
        - title: "Improving the Accuracy-Diversity Trade-off in Recommender Systems with Reranking Strategies"
          date_end: ''
          date_start: '2023-09-01'
          description: |
            **Master's Thesis, Stefan Russman** (Co-advisor)
            Research on optimizing recommender systems to balance accuracy with diversity through post-processing reranking techniques.
            _In progress_
            
        - title: "Analysis of Cross-Platform User Behavior on the Example of Reddit and YouTube Comments"
          date_end: '2021-03-01'
          date_start: '2020-09-01'
          description: |
            **Bachelor's Thesis, Volker Seiser** (Co-advisor)
            Investigated how user language in YouTube comments changes after videos are shared on Reddit's conspiracy forums, finding measurable linguistic convergence between platforms.
            _Completed_
    design: 
      columns: '2'
#  - block: accomplishments
#    content:
#      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
#      # title: 'Accomplish&shy;ments'
#      title: 'Accomplish&shy;ments'
#      subtitle:
#      # Date format: https://wowchemy.com/docs/customization/#date-format
#      date_format: Jan 2006
#      # Accomplishments.
#      #   Add/remove as many `item` blocks below as you like.
#      #   `title`, `organization`, and `date_start` are the required parameters.
#      #   Leave other parameters empty if not required.
#      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
#      items:
#        - certificate_url: https://www.coursera.org
#          date_end: ''
#          date_start: '2021-01-25'
#          description: ''
#          organization: Coursera
#          organization_url: https://www.coursera.org
#          title: Neural Networks and Deep Learning
#          url: ''
#        - certificate_url: https://www.edx.org
#          date_end: ''
#          date_start: '2021-01-01'
#          description: Formulated informed blockchain models, hypotheses, and use cases.
#          organization: edX
#          organization_url: https://www.edx.org
#          title: Blockchain Fundamentals
#          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
#        - certificate_url: https://www.datacamp.com
#          date_end: '2020-12-21'
#          date_start: '2020-07-01'
#          description: ''
#          organization: DataCamp
#          organization_url: https://www.datacamp.com
#          title: 'Object-Oriented Programming in R'
#          url: ''
#    design:
#      columns: '2'
#  - block: collection
#    id: posts
#    content:
#      title: Recent Posts
#      subtitle: ''
#      text: ''
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
#      # Filter on criteria
#      filters:
#        folders:
#          - post
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
#      # Choose how many pages you would like to offset by
#      offset: 0
#      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
#      # Choose a layout view
#      view: compact
#      columns: '2'
#  - block: markdown
#    content:
#      title: Gallery
#      subtitle: ''
#      text: |-
#        {{< gallery album="demo" >}}
#    design:
#      columns: '1'
#  - block: collection
#    id: featured
#    content:
#      title: Featured Publications
#      filters:
#        folders:
#          - publication
#        featured_only: true
#    design:
#      columns: '2'
#      view: card
  - block: collection
    id: talks
    content:
      title: Invited Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Have a question or want to work together? I'd love to hear from you! Please use the form below to send me a message, and I will get back to you as soon as possible. 

      # Contact (add or remove contact options as necessary)
      email: tduricic90@gmail.com
      # phone: +43 316 873-30844
      address:
        street: Sandgasse 34
        city: Graz
        region: 
        postcode: '8010'
        country: Austria
        country_code: AT
      contact_links:
        - icon: linkedin
          icon_pack: fab
          name: DM Me
          link: 'https://www.linkedin.com/in/tduricic/'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
