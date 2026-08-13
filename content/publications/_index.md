---
title: Publications
type: landing

sections:
  - block: markdown
    content:
      title: Publications
      text: |-
        My publications span **biomedical AI, natural language processing, large language models, multimodal learning, explainable AI, and data-efficient learning**.

        Browse them by publication type:

        **[Journal Articles →](/journal-articles/)** &nbsp;&nbsp; **[Conference Papers →](/conference-papers/)** &nbsp;&nbsp; [Google Scholar ↗](https://scholar.google.com/citations?user=Aw4cEzMAAAAJ)
    design:
      columns: '1'

  - block: collection
    id: journals
    content:
      title: 'Journal Articles'
      text: 'Recent peer-reviewed journal publications.'
      count: 6
      sort_by: Date
      sort_ascending: false
      filters:
        folders:
          - publications
        publication_type: article-journal
      archive:
        enable: true
        text: 'View all journal articles →'
        link: /journal-articles/
    design:
      view: citation
      columns: 1
      show_read_time: false
      show_read_more: false

  - block: collection
    id: conferences
    content:
      title: 'Conference Papers'
      text: 'Recent conference and workshop papers.'
      count: 6
      sort_by: Date
      sort_ascending: false
      filters:
        folders:
          - publications
        publication_type: paper-conference
      archive:
        enable: true
        text: 'View all conference papers →'
        link: /conference-papers/
    design:
      view: citation
      columns: 1
      show_read_time: false
      show_read_more: false
---
