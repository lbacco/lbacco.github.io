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

  <section class="info-grid">

  <!-- RESEARCH INTERESTS -->
  <div class="info-column">
    <h3>Research Interests</h3>

    <div class="interest-item">
      <span class="item-icon">◌</span>
      <span>Large Language Models & NLP</span>
    </div>

    <div class="interest-item">
      <span class="item-icon">⌕</span>
      <span>Explainable & Reliable AI</span>
    </div>

    <div class="interest-item">
      <span class="item-icon">◇</span>
      <span>Multimodal & Biomedical AI</span>
    </div>

    <div class="interest-item">
      <span class="item-icon">∿</span>
      <span>Data-efficient Learning</span>
    </div>
  </div>

  <!-- EXPERIENCE -->
  <div class="info-column">
    <h3>Experience</h3>

    <div class="timeline-item">
      <div class="item-logo">
        <img src="/images/logos/ucbm.svg"
             alt="Università Campus Bio-Medico di Roma">
      </div>
    
      <div class="item-content">
        <div class="item-header">
          <strong>Università Campus Bio-Medico di Roma</strong>
          <span class="item-date">2025 – Present</span>
        </div>
    
        <div class="item-role">
          Assistant Professor
        </div>
      </div>
    </div>

    <div class="timeline-item">
      <div class="item-logo">
        <img src="/images/logos/ucbm.png"
             alt="Università Campus Bio-Medico di Roma">
      </div>

      <div class="item-content">
        <div class="item-header">
          <strong>Università Campus Bio-Medico di Roma</strong>
          <span class="item-date">2022 – 2025</span>
        </div>

        <div class="item-role">
          Postdoctoral Researcher
        </div>
      </div>
    </div>


    <div class="timeline-item">
      <div class="item-logo">
        <img src="/images/logos/groningen.png"
             alt="University of Groningen">
      </div>

      <div class="item-content">
        <div class="item-header">
          <strong>University of Groningen</strong>
          <span class="item-date">2022</span>
        </div>

        <div class="item-role">
          Visiting PhD Student, Computational Linguistics
        </div>
      </div>
    </div>


    <div class="timeline-item">
      <div class="item-logo">
        <img src="/images/logos/ucbm.png"
             alt="Università Campus Bio-Medico di Roma">
      </div>

      <div class="item-content">
        <div class="item-header">
          <strong>Università Campus Bio-Medico di Roma</strong>
          <span class="item-date">2019 – 2022</span>
        </div>

        <div class="item-role">
          PhD Candidate
        </div>
      </div>
    </div>
  </div>


  <!-- EDUCATION -->
  <div class="info-column">
    <h3>Education</h3>

    <div class="timeline-item">
      <div class="item-logo">
        <img src="/images/logos/ucbm.png"
             alt="Università Campus Bio-Medico di Roma">
      </div>

      <div class="item-content">
        <div class="item-header">
          <strong>Università Campus Bio-Medico di Roma</strong>
          <span class="item-date">2023</span>
        </div>

        <div class="item-role">
          PhD in Information Technology for Biomedicine
        </div>

        <div class="item-description">
          Thesis:
          <span class="thesis-title">
            Exploring New Technologies in Healthcare:
            Advancing Natural Language Processing
          </span>
        </div>
      </div>
    </div>


    <div class="timeline-item">
      <div class="item-logo">
        <img src="/images/logos/ucbm.png"
             alt="Università Campus Bio-Medico di Roma">
      </div>

      <div class="item-content">
        <div class="item-header">
          <strong>Università Campus Bio-Medico di Roma</strong>
          <span class="item-date">2019</span>
        </div>

        <div class="item-role">
          MSc in Biomedical Engineering
          <span class="degree-grade">— 110/110 cum laude</span>
        </div>

        <div class="item-description">
          Thesis:
          <span class="thesis-title">
            Development of a motion control system for an anthropomorphic
            manipulator based on online extraction of muscle synergies
          </span>
        </div>
      </div>
    </div>
  </div>

</section>


<style>
.info-grid {
  display: grid;
  grid-template-columns: 0.85fr 1.15fr 1.15fr;
  gap: 56px;
  width: 100%;
  margin: 2.5rem auto;
}

.info-column {
  min-width: 0;
}

.info-column h3 {
  font-size: 1.05rem;
  font-weight: 700;
  margin: 0;
  padding-bottom: 0.8rem;
  border-bottom: 1px solid rgba(128, 128, 128, 0.35);
}


/* Research interests */

.interest-item {
  display: flex;
  align-items: center;
  gap: 12px;

  min-height: 52px;
  padding: 10px 0;

  border-bottom: 1px solid rgba(128, 128, 128, 0.25);

  font-size: 0.95rem;
}

.item-icon {
  flex: 0 0 18px;
  font-size: 1rem;
  color: #94a5ff;
}


/* Experience / Education */

.timeline-item {
  display: flex;
  gap: 12px;

  padding: 15px 0;

  border-bottom: 1px solid rgba(128, 128, 128, 0.25);
}

.item-logo {
  width: 30px;
  height: 30px;

  flex: 0 0 30px;

  display: flex;
  align-items: center;
  justify-content: center;

  border-radius: 5px;
  background: #fff;

  overflow: hidden;
}

.item-logo img {
  width: 100%;
  height: 100%;
  object-fit: contain;
}

.item-content {
  flex: 1;
  min-width: 0;
}

.item-header {
  display: flex;
  align-items: baseline;
  justify-content: space-between;
  gap: 16px;
}

.item-header strong {
  color: #94a5ff;
  font-size: 0.95rem;
  line-height: 1.3;
}

.item-date {
  flex-shrink: 0;

  font-size: 0.72rem;
  opacity: 0.7;
  white-space: nowrap;
}

.item-role {
  margin-top: 2px;

  font-size: 0.9rem;
  line-height: 1.35;

  opacity: 0.75;
}

.item-description {
  margin-top: 4px;

  font-size: 0.76rem;
  line-height: 1.4;

  opacity: 0.85;
}

.thesis-title {
  color: #94a5ff;
}

.degree-grade {
  white-space: nowrap;
}


/* Tablet */

@media (max-width: 1000px) {
  .info-grid {
    grid-template-columns: 1fr 1fr;
    gap: 36px;
  }

  .info-column:first-child {
    grid-column: 1 / -1;
  }
}


/* Mobile */

@media (max-width: 700px) {
  .info-grid {
    grid-template-columns: 1fr;
    gap: 32px;
  }

  .info-column:first-child {
    grid-column: auto;
  }

  .item-header {
    flex-wrap: wrap;
    gap: 4px 12px;
  }
}
</style>

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
