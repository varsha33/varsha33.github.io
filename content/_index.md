---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    id: home
    content:
      username: me
      text: |-
        I am a postdoctoral researcher at Saarland University. My research focuses on multimodal language understanding, gesture and discourse modeling, affective computing, and human-centered machine learning.

        I am particularly interested in how verbal and non-verbal signals interact, how multimodal systems reason about people and behavior, and how to build language and vision-language models that are both more grounded and more socially aware.

        ### News

        - **June 25, 2026**: Gave a talk at the RTG Neuroexplicit group: *Beyond Transcript: From Understanding Non-Verbal Signals to Generating Meaningful Behaviors*.
        - **May 28, 2026**: New preprint out: [*Semantic Motion Anchors: Bridging Motion and Meaning in Co-Speech Gestures*](https://arxiv.org/abs/2605.30608).
        - **May 28, 2026**: New preprint out: [*MuPHI: Learning Implicit Multimodal Harm Reasoning via Semantically Grounded Reward Optimization*](https://arxiv.org/abs/2605.29951).
      headings:
        about: 'About'
        education: ''
        interests: 'Research Interests'
    design:
      background:
        gradient_mesh:
          enable: false
      name:
        size: md
      avatar:
        size: medium
        shape: rounded
  - block: collection
    id: publications
    content:
      title: 'Publications'
      text: 'Selected publications. For a fuller list, see my [Google Scholar](https://scholar.google.com/citations?user=Pv4qSeEAAAAJ&hl=en).'
      count: 0
      filters:
        folders:
          - publications
      order: desc
    design:
      view: citation
  - block: markdown
    id: teaching
    content:
      title: 'Teaching & Supervision'
      subtitle: ''
      text: |-
        ### Master Students

        - **Tsan Tsai Chan** (Jan 2025 - Oct 2025): worked on [attention imbalances in vision-language models](https://arxiv.org/abs/2601.12430).
        - **Toshiki Nakai** (Aug 2025 - Jan 2026): worked on the [generation-step-aware framework for multilingual speech-text models](https://arxiv.org/abs/2601.17387).
        - **Mohamad Salman** (Jan 2025 - Apr 2026): worked on [*Semantic Motion Anchors*](https://arxiv.org/abs/2605.30608), where he helped develop the anchor generation for the preprint.

        ### Currently Ongoing

        - **Zhanna** (Mar 2025 - present): shortcut learning in VLMs.
        - **Diana** (Mar 2025 - present): investigating irony understanding of VLMs.

        ### Research Student Experience

        - **Fan Wu**: working toward emotion understanding in VLMs.

        ### Teaching

        - **[Multimodal Language Understanding](https://exultant-desk-092.notion.site/d1f22b1659d344e4b1d03d8e5b71b069?v=77953936d5274e00aafffaba40e6df08)**, Saarland University, Winter 2024 and Summer 2026.
        - **Previous teaching experience at NUS** (Jan 2019 - Dec 2021): IS4152 Affective Computing and CS1010E Programming Methodology for Python/C.
    design:
      columns: '1'
  - block: markdown
    id: talks
    content:
      title: 'Talks'
      subtitle: ''
      text: |-
        - **Beyond Transcript: From Understanding Non-Verbal Signals to Generating Meaningful Behaviors**<br>
          RTG Neuroexplicit group, June 25, 2026.
    design:
      columns: '1'
  - block: markdown
    id: contact
    content:
      title: 'Contact'
      subtitle: ''
      text: |-
        - Email: [vsuresh@lst.uni-saarland.de](mailto:vsuresh@lst.uni-saarland.de)
        - LinkedIn: [varsha-suresh-2bb773b1](https://www.linkedin.com/in/varsha-suresh-2bb773b1/)
        - Google Scholar: [profile](https://scholar.google.com/citations?user=Pv4qSeEAAAAJ&hl=en)
        - CV: [Download PDF](/uploads/resume.pdf)
    design:
      columns: '1'
---
