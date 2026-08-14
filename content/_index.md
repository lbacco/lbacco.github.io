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


  # Research statement
  - block: markdown
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        My research focuses on **Artificial Intelligence**, with particular
        interests in **Natural Language Processing, Large Language Models,
        multimodal learning, explainable AI, and biomedical applications**.

        I am particularly interested in developing **reliable and data-efficient
        machine learning methods for low-data and specialized-domain settings**,
        and in understanding how modern AI models can be effectively adapted,
        evaluated, and interpreted in interdisciplinary applications.

        My current research spans biomedical NLP and LLMs, multimodal learning,
        physiological signals, computer vision, generative AI, and time-series
        modelling.
    design:
      columns: '1'

  # Research themes
  - block: markdown
    content:
      title: 'Research Interests'
      subtitle: ''
      text: |-
        **Natural Language Processing & Large Language Models**  
        Transformer-based language models, domain adaptation, fine-tuning,
        representation learning, distillation, and retrieval-augmented generation.

        **Biomedical & Multimodal AI**  
        AI methods integrating text, images, physiological signals, and other
        heterogeneous biomedical data.

        **Explainable & Reliable AI**  
        Interpretability, model behaviour, robustness, and reliability of
        machine learning and deep learning systems.

        **Data-efficient Learning**  
        Machine learning approaches for specialized domains where annotated
        data are limited or expensive to obtain.
    design:
      columns: '1'
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

  # NEWS_BLOCK_START
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
  # NEWS_BLOCK_END

---
