---
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      username: admin

  - block: features
    content:
      title: Skills
      items:
        - name: Python
          icon: python
          icon_pack: fas
        - name: Statistics
          icon: chart-line
          icon_pack: fas
        - name: R
          icon: r-project
          icon_pack: fab

  - block: experience
    content:
      title: Research Appointments
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Postdoctoral Fellow in Biomedical Data Science
          company: Center for Technology and Behavioral Health, Geisel School of Medicine at Dartmouth College
          company_url: 'https://www.c4tbh.org/'
          company_logo: dartmouth
          location: Hanover, NH
          date_start: '2023-07-01'
          date_end: ''
          description: ''
        - title: Clinical Psychology Resident
          company: The Warren Alpert Medical School, Brown University
          company_url: 'https://clinical-psychology.med.brown.edu/internship'
          company_logo: brown
          location: Providence, RI
          date_start: '2022-07-01'
          date_end: '2023-06-30'
          description: ''
        - title: Doctoral Student Researcher
          company: Klein Developmental Psychopathology Lab, Stony Brook University
          company_url: 'https://you.stonybrook.edu/dkleinlab/'
          company_logo: sbu
          location: Stony Brook, NY
          date_start: '2017-09-01'
          date_end: '2023-06-30'
          description: ''
        - title: Research Specialist and Clinical Interviewer
          company: Mind-Body Clinical Research Center, Stony Brook University School of Medicine
          company_url: 'https://neuro.stonybrookmedicine.edu/centers/mind-body'
          company_logo: sbu
          location: Stony Brook, NY
          date_start: '2015-06-01'
          date_end: '2017-08-30'
          description: ''
        - title: Research Specialist and EEG Technician
          company: Department of Psychiatry, Stony Brook University School of Medicine
          company_url: 'https://renaissance.stonybrookmedicine.edu/psychiatry/research/research_programs'
          company_logo: sbu
          location: Stony Brook, NY
          date_start: '2015-06-01'
          date_end: '2016-05-31'
          description: ''
        - title: Graduate Student Researcher
          company: Department of Psychology, Stony Brook University
          company_url: 'https://renaissance.stonybrookmedicine.edu/psychiatry/research/research_programs'
          company_logo: sbu
          location: Stony Brook, NY
          date_start: '2014-05-01'
          date_end: '2015-05-31'
          description: ''
    id: appointments 
    design:
      columns: '2'

  - block: portfolio
    content:
      buttons:
      - name: All
        tag: '*'
      - name: Machine Learning
        tag: Machine Learning
      - name: Reinforcement Learning
        tag: Reinforcement Learning
      default_button_index: 0
      filters:
        folders:
        - project
      title: Projects
    design:
      columns: "1"
      flip_alt_rows: false
      view: showcase
    id: projects

  - block: collection
    id: featured
    content:
      filters:
        featured_only: true
        folders:
        - publication
      title: Featured Publication
    design:
      view: card
      columns: '2'

  - block: collection
    content:
      filters:
        exclude_featured: true
        folders:
        - publication
      text: |-
      title: Additional Selected Publications
    design:
      columns: "2"
      view: citation
    id: selected-works

  - block: contact
    content:
      address:
        city: Lebanon
        country: United States
        country_code: US
        postcode: "03766"
        region: NH
        street: 46 Centerra Parkway, Evergreen Center, Suite 300, Office 338S
      email: daniel.m.mackin@dartmouth.edu
      text: If interested in collaborating, contact me via email. 
      title: Contact
    design:
      columns: "2"
    id: contact
  title: null
  type: landing
---
