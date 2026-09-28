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
        I am a postdoctoral researcher in the Multimodal Language Processing Group at the Max Planck Institute for Informatics, led by [Prof. Dr. Vera Demberg](https://www.uni-saarland.de/lehrstuhl/demberg.html), and am affiliated with the Department of Language Science and Technology at Saarland University.

        My research looks beyond the transcript. Human communication is multimodal: meaning is carried not only by words but by gesture, facial expression, and timing. I study how these verbal and non-verbal signals interact, and build language and vision-language models that are more grounded in this multimodal context and more socially aware.

        My recent work spans three directions:
        - **Gesture and discourse:** using co-speech gestures to improve discourse and turn-taking modelling in language models (ACL 2025, EACL Findings 2026), and generating semantically meaningful gestures (NeurIPS 2026).
        - **Multimodal pragmatics and reasoning:** diagnosing how vision-language models handle sarcasm, irony, implicit harm, and other pragmatic phenomena, and why they fail.
        - **Human-centred applications:** from LLM-driven gesture coaching for public speaking (UIST 2025) to affective computing and fair facial expression recognition.

        <div id="news" class="varsha-bio-heading">
          <div class="varsha-bio-heading-icon"><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M12 7.5h1.5m-1.5 3h1.5m-7.5 3h7.5m-7.5 3h7.5m3-9h3.375c.621 0 1.125.504 1.125 1.125V18a2.25 2.25 0 0 1-2.25 2.25M16.5 7.5V18a2.25 2.25 0 0 0 2.25 2.25M16.5 7.5V4.875c0-.621-.504-1.125-1.125-1.125H4.125C3.504 3.75 3 4.254 3 4.875V18a2.25 2.25 0 0 0 2.25 2.25h13.5M6 7.5h3v3H6v-3Z" /></svg></div>
          <h2>News</h2>
        </div>

        - **September 2026**: [*Semantic Motion Anchors: Bridging Motion and Meaning in Co-Speech Gestures*](https://arxiv.org/abs/2605.30608) accepted at **NeurIPS 2026**!
        - **September 2026**: *Do Motion Tokenizers for Co-Speech Gesture Generation Encode Gesture Semantics?* accepted at the **MINT Workshop @ EMNLP 2026**.
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
  - block: markdown
    id: publications
    content:
      title: 'Publications'
      text: |-
        <div class="varsha-publication-list">
          <div class="varsha-publication-year">2026</div>

          <div class="varsha-publication-entry">
            <p class="varsha-publication-title">Semantic Motion Anchors: Bridging Motion and Meaning in Co-Speech Gestures</p>
            <p class="varsha-publication-authors"><strong>Varsha Suresh</strong>, Mohammad Mahdi Abootorabi, Mohamed Salman, M Hamza Mughal, Christian Theobalt, Ashwin Ram, Jürgen Steimle, Vera Demberg</p>
            <p class="varsha-publication-venue"><em>NeurIPS</em>, 2026. <a href="https://arxiv.org/abs/2605.30608">arXiv</a></p>
          </div>

          <div class="varsha-publication-entry">
            <p class="varsha-publication-title">Do Motion Tokenizers for Co-Speech Gesture Generation Encode Gesture Semantics?</p>
            <p class="varsha-publication-authors"><strong>Varsha Suresh</strong>, Divij Jain, Jia Liu, M Hamza Mughal, Vera Demberg</p>
            <p class="varsha-publication-venue"><em>MINT Workshop @ EMNLP</em>, 2026.</p>
          </div>

          <div class="varsha-publication-entry">
            <p class="varsha-publication-title">MuPHI: Learning Implicit Multimodal Harm Reasoning via Semantically Grounded Reward Optimization</p>
            <p class="varsha-publication-authors">Anisha Saha, <strong>Varsha Suresh</strong>, Teodora Kamova, Sophia Wiedmann, Timothy Hospedales, Vera Demberg</p>
            <p class="varsha-publication-venue"><em>arXiv preprint</em>, 2026. <a href="https://arxiv.org/abs/2605.29951">arXiv</a></p>
          </div>

          <div class="varsha-publication-entry">
            <p class="varsha-publication-title">Generation-Step-Aware Framework for Cross-Modal Representation and Control in Multilingual Speech-Text Models</p>
            <p class="varsha-publication-authors">Toshiki Nakai, <strong>Varsha Suresh</strong>, Vera Demberg</p>
            <p class="varsha-publication-venue"><em>arXiv preprint</em>, 2026. <a href="https://arxiv.org/abs/2601.17387">arXiv</a></p>
          </div>

          <div class="varsha-publication-entry">
            <p class="varsha-publication-title">System-Mediated Attention Imbalances Make Vision-Language Models Say Yes</p>
            <p class="varsha-publication-authors">Tsan Tsai Chan, <strong>Varsha Suresh</strong>, Anisha Saha, Michael Hahn, Vera Demberg</p>
            <p class="varsha-publication-venue"><em>Findings of the Association for Computational Linguistics: ACL</em>, 2026. <a href="https://arxiv.org/abs/2601.12430">arXiv</a></p>
          </div>

          <div class="varsha-publication-entry">
            <p class="varsha-publication-title">Modeling Turn-Taking with Semantically Informed Gestures</p>
            <p class="varsha-publication-authors"><strong>Varsha Suresh</strong>, M Hamza Mughal, Christian Theobalt, Vera Demberg</p>
            <p class="varsha-publication-venue"><em>Findings of the Association for Computational Linguistics: EACL</em>, 2026.</p>
          </div>

          <div class="varsha-publication-entry">
            <p class="varsha-publication-title">MUStReason: A Benchmark for Diagnosing Pragmatic Reasoning in Video-LMs for Multimodal Sarcasm Detection</p>
            <p class="varsha-publication-authors">Anisha Saha, <strong>Varsha Suresh</strong>, Timothy Hospedales, Vera Demberg</p>
            <p class="varsha-publication-venue"><em>LREC</em>, 2026. <a href="https://aclanthology.org/2026.lrec-1.769.pdf">PDF</a> · <a href="https://arxiv.org/abs/2510.23727">arXiv</a></p>
          </div>

          <div class="varsha-publication-entry">
            <p class="varsha-publication-title">PragMatch: Separating Pragmatic Incongruity from Cross-Modal Mismatch in Large Vision-Language Models</p>
            <p class="varsha-publication-authors">Zhanna Mukhametsharip, Vera Demberg, <strong>Varsha Suresh</strong></p>
            <p class="varsha-publication-venue"><em>arXiv preprint</em>, 2026. <a href="https://arxiv.org/abs/2608.09772">arXiv</a></p>
          </div>

          <div class="varsha-publication-entry">
            <p class="varsha-publication-title">DnD Group Gesture Dataset</p>
            <p class="varsha-publication-authors">Muhammad Hamza Mughal, Rishabh Dabral, Ikhsanul Habibie, Lucia Donatelli, Marc Habermann, <strong>Varsha Suresh</strong>, Vera Demberg, Christian Theobalt</p>
            <p class="varsha-publication-venue"><em>Dataset</em>, Edmond (Max Planck research data repository), 2026. <a href="https://doi.org/10.17617/3.IPFYCC">DOI</a></p>
          </div>

          <div class="varsha-publication-year">2025</div>

          <div class="varsha-publication-entry">
            <p class="varsha-publication-title">Enhancing Spoken Discourse Modeling in Language Models Using Gestural Cues</p>
            <p class="varsha-publication-authors"><strong>Varsha Suresh</strong>, M Hamza Mughal, Christian Theobalt, Vera Demberg</p>
            <p class="varsha-publication-venue"><em>ACL</em>, 2025. Oral presentation (Top 8%).</p>
          </div>

          <div class="varsha-publication-entry">
            <p class="varsha-publication-title">GestureCoach: Rehearsing for Engaging Talks with LLM-Driven Gesture Recommendations</p>
            <p class="varsha-publication-authors">Ashwin Ram, <strong>Varsha Suresh</strong>, Artin Saberpour Abadian, Vera Demberg, Jürgen Steimle</p>
            <p class="varsha-publication-venue"><em>UIST</em>, 2025.</p>
          </div>

          <div class="varsha-publication-entry">
            <p class="varsha-publication-title">Hybrid Multi-view Approach Towards Augmenting Large Language Models for Human Activity Recognition</p>
            <p class="varsha-publication-authors">Suman Bhoi, <strong>Varsha Suresh</strong>, Hsu Wynne, Lee Mong Li</p>
            <p class="varsha-publication-venue"><em>ECAI</em>, 2025.</p>
          </div>

          <div class="varsha-publication-entry">
            <p class="varsha-publication-title">Synthetic Data Augmentation for Cross-domain Implicit Discourse Relation Recognition</p>
            <p class="varsha-publication-authors">Frances Yung, <strong>Varsha Suresh</strong>, Zaynab Reza, Mansoor Ahmad, Vera Demberg</p>
            <p class="varsha-publication-venue"><em>SIGDial</em>, 2025.</p>
          </div>

          <div class="varsha-publication-year">2024</div>

          <div class="varsha-publication-entry">
            <p class="varsha-publication-title">An Adapter-Based Unified Model for Multiple Spoken Language Processing Tasks</p>
            <p class="varsha-publication-authors"><strong>Varsha Suresh</strong>, Salah Aït-Mokhtar, Caroline Brun, Ioan Calapodescu</p>
            <p class="varsha-publication-venue"><em>ICASSP</em>, 2024.</p>
          </div>

          <div class="varsha-publication-year">2023</div>

          <div class="varsha-publication-entry">
            <p class="varsha-publication-title">Critically examining the Domain Generalizability of Facial Expression Recognition models</p>
            <p class="varsha-publication-authors"><strong>Varsha Suresh</strong>, Gerard Yeo, Desmond C. Ong</p>
            <p class="varsha-publication-venue"><em>arXiv preprint</em>, 2023. <a href="https://arxiv.org/pdf/2106.15453">arXiv</a></p>
          </div>

          <div class="varsha-publication-year">2022</div>

          <div class="varsha-publication-entry">
            <p class="varsha-publication-title">Shape-Based Conditional Neural Field for Wrist-Worn Change-Point Detection</p>
            <p class="varsha-publication-authors">Yuang Shi, <strong>Varsha Suresh</strong>, Ooi Wei Tsang</p>
            <p class="varsha-publication-venue"><em>PerCom Workshops</em>, 2022.</p>
          </div>

          <div class="varsha-publication-entry">
            <p class="varsha-publication-title">Using Positive Matching Contrastive Loss with Facial Action Units to mitigate bias in Facial Expression Recognition</p>
            <p class="varsha-publication-authors"><strong>Varsha Suresh</strong>, Desmond C. Ong</p>
            <p class="varsha-publication-venue"><em>ACII</em>, 2022.</p>
          </div>

          <div class="varsha-publication-entry">
            <p class="varsha-publication-title">Context-Dependent Deep Learning for Affective Computing</p>
            <p class="varsha-publication-authors"><strong>Varsha Suresh</strong></p>
            <p class="varsha-publication-venue"><em>ACII Workshops and Demos</em>, 2022.</p>
          </div>

          <div class="varsha-publication-year">2021</div>

          <div class="varsha-publication-entry">
            <p class="varsha-publication-title">Using knowledge-embedded attention to augment pre-trained language models for fine-grained emotion recognition</p>
            <p class="varsha-publication-authors"><strong>Varsha Suresh</strong>, Desmond C. Ong</p>
            <p class="varsha-publication-venue"><em>ACII</em>, 2021. <a href="https://arxiv.org/abs/2108.00194">arXiv</a></p>
          </div>

          <div class="varsha-publication-entry">
            <p class="varsha-publication-title">A systematic evaluation of domain adaptation in facial expression recognition</p>
            <p class="varsha-publication-authors">Yan San Kong, <strong>Varsha Suresh</strong>, Jonathan Soh, Desmond C. Ong</p>
            <p class="varsha-publication-venue"><em>arXiv preprint</em>, 2021. <a href="https://arxiv.org/abs/2106.15453v1">arXiv</a></p>
          </div>

          <div class="varsha-publication-entry">
            <p class="varsha-publication-title">Not all negatives are equal: Label-aware contrastive loss for fine-grained text classification</p>
            <p class="varsha-publication-authors"><strong>Varsha Suresh</strong>, Desmond C. Ong</p>
            <p class="varsha-publication-venue"><em>EMNLP</em>, 2021.</p>
          </div>

          <div class="varsha-publication-year">2016</div>

          <div class="varsha-publication-entry">
            <p class="varsha-publication-title">A novel technique for identifying attentional selection in a dichotic environment</p>
            <p class="varsha-publication-authors">Priya Shree, Piyush Swami, <strong>Varsha Suresh</strong>, Tapan Kumar Gandhi</p>
            <p class="varsha-publication-venue"><em>INDICON</em>, 2016.</p>
          </div>
        </div>
    design:
      columns: '1'
  - block: markdown
    id: teaching
    content:
      title: 'Teaching & Supervision'
      subtitle: ''
      text: |-
        <div class="varsha-people">
          <div class="varsha-subheading">Current Students</div>

          <div class="varsha-person">
            <div class="varsha-person-head"><span class="varsha-person-name">Zhanna Mukhametsharip</span><span class="varsha-person-dates">Mar 2025 – present</span></div>
            <p class="varsha-person-topic">Pragmatic incongruity in large vision-language models (<a href="https://arxiv.org/abs/2608.09772"><em>PragMatch</em></a>)</p>
          </div>

          <div class="varsha-person">
            <div class="varsha-person-head"><span class="varsha-person-name">Diana Pavelock</span><span class="varsha-person-dates">Mar 2025 – present</span></div>
            <p class="varsha-person-topic">Investigating irony understanding in large vision-language models</p>
          </div>

          <div class="varsha-person">
            <div class="varsha-person-head"><span class="varsha-person-name">Fan Wu</span><span class="varsha-person-dates">Research student</span></div>
            <p class="varsha-person-topic">Towards emotion understanding in vision-language models</p>
          </div>

          <div class="varsha-subheading">Completed Students</div>

          <div class="varsha-person">
            <div class="varsha-person-head"><span class="varsha-person-name">Mohamed Salman</span><span class="varsha-person-dates">Jan 2025 – Apr 2026</span></div>
            <p class="varsha-person-topic">Semantic anchor generation for co-speech gestures (<a href="https://arxiv.org/abs/2605.30608"><em>Semantic Motion Anchors</em></a>, NeurIPS 2026)</p>
          </div>

          <div class="varsha-person">
            <div class="varsha-person-head"><span class="varsha-person-name">Toshiki Nakai</span><span class="varsha-person-dates">Aug 2025 – Jan 2026</span></div>
            <p class="varsha-person-topic">Generation-step-aware cross-modal representation and control in multilingual speech-text models (<a href="https://arxiv.org/abs/2601.17387">arXiv</a>)</p>
          </div>

          <div class="varsha-person">
            <div class="varsha-person-head"><span class="varsha-person-name">Tsan Tsai Chan</span><span class="varsha-person-dates">Jan 2025 – Oct 2025</span></div>
            <p class="varsha-person-topic">Attention imbalances in vision-language models (<a href="https://arxiv.org/abs/2601.12430"><em>System-Mediated Attention Imbalances</em></a>, Findings of ACL 2026)</p>
          </div>

          <div class="varsha-subheading">Teaching</div>

          <div class="varsha-person">
            <div class="varsha-person-head"><span class="varsha-person-name"><a href="https://exultant-desk-092.notion.site/d1f22b1659d344e4b1d03d8e5b71b069?v=77953936d5274e00aafffaba40e6df08">Multimodal Language Understanding</a></span><span class="varsha-person-dates">Winter 2024, Summer 2026</span></div>
            <p class="varsha-person-topic">Seminar, Saarland University</p>
          </div>

          <div class="varsha-person">
            <div class="varsha-person-head"><span class="varsha-person-name">National University of Singapore</span><span class="varsha-person-dates">Jan 2019 – Dec 2021</span></div>
            <p class="varsha-person-topic">IS4152 Affective Computing; CS1010E Programming Methodology (Python/C)</p>
          </div>
        </div>
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
        - Email: [vsuresh@mpi-inf.mpg.de](mailto:vsuresh@mpi-inf.mpg.de)
        - LinkedIn: [varsha-suresh-2bb773b1](https://www.linkedin.com/in/varsha-suresh-2bb773b1/)
        - Google Scholar: [profile](https://scholar.google.com/citations?user=Pv4qSeEAAAAJ&hl=en)
  
    design:
      columns: '1'
---
