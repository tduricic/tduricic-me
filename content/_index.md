---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
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
          description: Literature synthesis, experimental design, data interpretation, critical thinking, effective communication of results, LaTeX, hypothesis testing, statistical analysis, research collaboration, grant proposal writing, knowledge of relevant research methodologies, and presentation skills for both technical and non-technical audiences.
          icon: chart-line
          icon_pack: fas
        - name: ML & Data Science
          description: Supervised/unsupervised learning, recommender systems (scikit-surprise, Elliot), deep and graph learning frameworks (PyTorch, PyG), data preprocessing and manipulation (pandas, NumPy, NetworkX), feature engineering, model evaluation and selection (scikit-learn, cross-validation), data visualization (Matplotlib, Seaborn), natural language processing (NLTK, spaCy, Transformers), time series analysis, anomaly detection, and dimensionality reduction techniques (PCA, t-SNE).
          icon: robot
          icon_pack: fas
        - name: Software Engineering
          description: Proficiency in object-oriented programming using Python and Java, software design patterns, database management with SQL and NoSQL (MySQL, PostgreSQL, Apache Solr, MongoDB), web development with Spring Boot, RESTful API design, deployment and management of applications on Linux servers, containerization and virtualization (Docker, Kubernetes), cloud services (AWS, GCP), and version control (Git).
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
        - title: University Assistant
          company: Graz University of Technology
          company_url: 'https://www.tugraz.at/home'
          company_logo: org-tug
          location: Graz, Austria
          date_start: '2018-10-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Conducting research in my area of study
              * Collaborating with other researchers or research teams
              * Assisting with grant proposals and funding applications
              * Presenting research findings at conferences or events
              * Teaching and mentoring undergraduate or graduate students
        - title: Researcher / Project Lead / Software Engineer / ML Engineer / Data Scientist
          company: Know-Center
          company_url: 'https://www.know-center.at/'
          company_logo: org-kc
          location: Graz, Austria
          date_start: '2016-03-01'
          date_end: ''
          description: |2-
              Responsibilities include:
              
              * Conducting research in various fields related to data science and machine learning
              * Leading and managing projects related to software engineering, machine learning, and data science, including project planning, implementation, and delivery
              * Developing software solutions and implementing machine learning models to solve complex business problems
              * Analyzing and interpreting data to gain insights and improve decision-making processes
              * Collaborating with internal and external stakeholders to deliver successful project outcomes, including grant proposal writing, presentations, and event organization
        - title: ERASMUS+ internship
          company: Know-Center
          company_url: 'https://www.know-center.at/'
          company_logo: org-kc
          location: Graz, Austria
          date_start: '2015-03-01'
          date_end: '2015-08-31'
          description: I researched real-time and trust-based recommender systems and wrote a master's thesis on "Real-Time Recommendations Based on Social Trust" under the guidance of Prof. Dr. Sc. Vedran Podobnik, Assoc.-Prof. Dr. Elisabeth Lex, and Dr. Emanuel Lacić. My thesis results were integrated into the internal ScaR framework (Scalable Recommendation-as-a-service).
        - title: Junior Android Developer
          company: FZI Research Center for Information Technology
          company_url: 'https://www.fzi.de/en/'
          company_logo: org-fzi
          location: Karlsruhe, Germany
          date_start: '2013-01-01'
          date_end: '2013-10-01'
          description: During the Erasmus+ student exchange program, I worked with the Informatics Institute of the Faculty of Economics and Business Engineering and FZI Research Center to develop a mobile app for capturing real-time student feedback. My Bachelor's thesis, titled "Mobile Live Interest Meter Application," was supervised by Prof. Dr. Rudi Studer and Dr. Verónica Rivera Pelayo.
        - title: Student developer in Ericsson Nikola Tesla Summer Camp
          company: Ericsson Nikola Tesla d.d.
          company_url: 'https://www.ericsson.hr/'
          company_logo: org-eri
          location: Zagreb, Croatia / Budapest, Hungary
          date_start: '2014-07-01'
          date_end: '2014-09-15'
          description: During a 5-week summer internship at Ericsson Nikola Tesla Summer Camp, I integrated a code plagiarism toolkit into the company's internal IDE using Javascript, HTML, CSS, and the Dojo toolkit. The program included 3 weeks in Zagreb and 2 weeks in Budapest, providing valuable experience in software development and insight into the telecommunications industry.      
    design:
      columns: '2'
  - block: collection
    id: publications
    content:
      title: Recent Publications
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
      title: Projects
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
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
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
        - title: Data Science in Business 2
          date_end: '2023-02-01'
          date_start: '2022-10-01'
          organization: Graz University of Technology and University of Graz
          organization_url: 'https://www.tugraz.at/studium/studienangebot/masterstudien/computational-social-systems'
          description: As one of three lecturers, I was responsible for instructing and grading practical sessions for the Data Science in Business 2 course, which is part of the Computational Social Systems Master's program offered jointly by Graz University of Technology and the University of Graz. During the course, I taught students about natural language processing, covering text cleaning, feature engineering, and popular Python libraries like Transformers. The final project involved working with financial textual data and helped students develop critical thinking and problem-solving skills.
        - title: Complexity Science
          date_end: '2019-02-01'
          date_start: '2018-10-01'
          organization: Graz University of Technology
          organization_url: 'https://www.tugraz.at/en/studying-and-teaching/degree-and-certificate-programmes/masters-degree-programmes/information-and-computer-engineering/'
          description: I served as a lecturer in the complexity science course, where I assisted my mentor in covering the topics presented in Chapter 7 of "Complexity - A Guided Tour" by Melanie Mitchell. My responsibilities included creating and grading student assignments related to the principles of complexity, fitness landscapes, and evolution of cooperation.
    design: 
      columns: '2'
  - block: accomplishments
    id: services
    content:
      title: Services
      date_format: Jan 2006
      items:
        - title: Session chairing and workshop organization
          date_end: '2023-02-01'
          date_start: '2022-10-01'
          organization: ''
          organization_url: ''
          description: ''
        - title: Program Committee Membership and Reviewing
          date_end: '2018-10-01'
          date_start: '2019-02-01'
          organization: ''
          organization_url: ''
          description:  |2-
              Responsibilities include:
              
              * Conducting research in various fields related to data science and machine learning
              * Leading and managing projects related to software engineering, machine learning, and data science, including project planning, implementation, and delivery
              * Developing software solutions and implementing machine learning models to solve complex business problems
              * Analyzing and interpreting data to gain insights and improve decision-making processes
              * Collaborating with internal and external stakeholders to deliver successful project outcomes, including grant proposal writing, presentations, and event organization
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
          organization: Know-Center and Institute of Interactive Systems and Data Science
          organization_url: 'https://www.tugraz.at/institute/isds/home'
          description: I received the Best Presentation Award at the institute's PhD retreat for the presentation of my PhD topic.
        - title: Travel Grant
          date_end: ''
          date_start: '2019-09-02'
          organization: Euro CSS
          organization_url: 'http://symposium.computationalsocialscience.eu/2019/'
          description: I received a travel grant to attend the European Symposium on Societal Challenges in Computational Social Science in Zurich, which focused on "Polarization and Radicalization."
        - title: Travel Grant
          date_end: ''
          date_start: '2019-09-02'
          organization: Euro CSS
          organization_url: 'http://summerschool.computationalsocialscience.eu/2019/'
          description: I received a travel grant to attend the third summer school on analyzing multimedia data in Berlin. The program covered computer vision, spatial and temporal analysis of urban spaces, and multimedia content models.
        - title: Erasmus+ Traineeship Scholarship
          date_end: '2015-08-31'
          date_start: '2015-02-01'
          organization: Erasmus+
          organization_url: 'https://erasmus-plus.ec.europa.eu/opportunities/opportunities-for-individuals/students/traineeships-abroad-for-students'
          description: With an Erasmus+ traineeship scholarship, I completed a 6-month internship at the Know-Center, finishing my master's thesis and gaining valuable skills.
        - title: Erasmus+ Student Exchange Scholarship
          date_end: '2012-08-31'
          date_start: '2011-09-01'
          organization: Erasmus+
          organization_url: 'https://erasmus-plus.ec.europa.eu/opportunities/opportunities-for-individuals/students/studying-abroad'
          description: I received an Erasmus+ scholarship to study for two semesters at the Karlsruhe Institute of Technology.
    design: 
      columns: '2'
  - block: accomplishments
    id: theses
    content:
      title: Co-Supervised Theses
      date_format: Jan 2006
      items:
        - title: Volker Seiser, "Analysis of cross-platform user behavior on the example of Reddit and YouTube comments."
          date_end: '2021-03-01'
          date_start: '2020-09-01' 
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
      title: Recent & Upcoming Talks
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
      phone: +43 316 873-30844
      address:
        street: Sandgasse 36
        city: Graz
        region: 
        postcode: '8010'
        country: Austria
        country_code: AT
      contact_links:
        - icon: linkedin
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/Twitter'
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
