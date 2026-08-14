---
title: 'Luca Bacco'
summary: 'Luca Bacco - AI Research Scientist'
date: 2026-08-13
type: landing

sections:

  # Welcome
  - block: markdown
    content:
      title: 'Welcome'
      subtitle: ''
      text: |-
        :wave: Welcome to my website! 
        I'm Luca, AI Research Scientist. 
        I currently hold the role of Assistant Professor in the
        [Intelligent Health Technology Lab](https://iht.unicampus.it/)
        at Università Campus Bio-Medico di Roma.

        The broad scientific question guiding my work is how to design
        AI systems that are not only accurate but also interpretable, 
        fairly evaluated, robust under domain-specific constraints,
        and able to integrate heterogeneous sources of information. 

        Here you can find information about me, my research, publications,
        projects, and recent activities.
        Want to get in touch? You can find my contact details on the
        left, or leave me [anonymous feedback](https://www.admonymous.co/lbacco). 😁
    design:
      columns: '1'

  # RESEARCH / EXPERIENCE / EDUCATION
  # =========================================================
  - block: profile-overview
    id: profile-overview
    content:

      research_interests:
        - name: 'NLP & Large Language Models'
          icon: 💬

        - name: 'Explainable & Reliable AI'
          icon: 🔍

        - name: 'Biomedical & Multimodal AI'
          icon: ⚕️

        - name: 'Data-efficient Learning'
          icon: 📊


      experience:

        - institution: 'Università Campus Bio-Medico di Roma'
          role: 'Assistant Professor'
          date: '09/2025 – present'
          logo: 'logos/ucbm.png'

        - institution: 'Università Campus Bio-Medico di Roma'
          role: 'Postdoctoral Researcher'
          date: '11/2022 – 08/2025'
          logo: 'logos/ucbm.png'

        - institution: 'University of Groningen'
          role: 'Visiting PhD Student, Computational Linguistics'
          date: '01/2022 - 07/2022'
          logo: 'logos/groningen.png'

        - institution: 'Università Campus Bio-Medico di Roma'
          role: 'PhD Candidate'
          date: '11/2019 – 10/2022'
          logo: 'logos/ucbm.png'


      education:

        - institution: 'Università Campus Bio-Medico di Roma'
          degree: 'PhD in Information Technology for Biomedicine'
          date: '2023'
          logo: 'images/logos/ucbm.png'
          thesis: 'Exploring New Technologies in Healthcare: Advancing Natural Language Processing'

        - institution: 'Università Campus Bio-Medico di Roma'
          degree: 'MSc in Biomedical Engineering — 110/110 cum laude'
          date: '2019'
          logo: 'images/logos/ucbm.png'
          thesis: 'Development of a motion control system for an anthropomorphic manipulator based on online extraction of muscle synergies'

  # PUBLICATIONS
  - block: collection
    id: publications
    content:
      title: 'Selected Publications'
      text: ''
      filters:
        folders:
          - publications
        featured_only: true
      archive:
        enable: true
        text: All publications
        link: /publications/
    design:
      view: citation

  # NEWS
  - block: collection
    id: news
    content:
      title: 'News'
      text: ''
      count: 5
      sort_by: Date
      sort_ascending: false
      filters:
        folders:
          - news
      archive:
        enable: true
        text: All news
        link: /news/
    design:
      view: date-title-summary
      columns: 1
      show_date: true
      show_read_time: false
      show_read_more: true

---
