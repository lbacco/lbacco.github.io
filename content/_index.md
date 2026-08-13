---
title: ''
summary: 'Luca Bacco - Assistant Professor and AI Research Scientist'
date: 2026-08-13
type: landing

sections:

  # Biography / profile
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    
    design:
      # Clean background, closer to the style we want
      background:
        gradient_mesh:
          enable: false

      name:
        size: md

      avatar:
        size: medium
        shape: circle

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

  # News
  - block: collection
    id: news
    content:
      title: 'News'
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
