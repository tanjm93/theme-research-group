---
title: Research
date: 2022-10-24

type: landing

sections:
  - block: markdown
    content:
      title: '<span style="color: white;">Research Overview</span>'
      subtitle: ''
      text: |
        <div style="background: rgba(0,0,0,0.5); padding: 5px 10px; border-radius: 8px;"> Much of our work focuses on developing chemistry-aware AI systems for electrochemical processes, moving beyond black-box approaches toward mechanism-informed, predictive workflows. Our long-term goal is to enable AI scientists as collaborative partners in accelerating solutions to global energy and environmental challenges.</div>
    design:
      columns: '1'
      background:
        image:
          filename: research_overview.jpg
          filters:
            brightness: 0.7  # Darken image so text is readable
          parallax: false
          position: center
          size: cover
          text_color_light: true  # Use light text on dark background
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: 'text-light'

  # - block: markdown
  #   content:
  #     title: 'Current Research Directions'
  #     subtitle: ''
  #     text: ''
  #   design:
  #     columns: '1'
  #     spacing:
  #       padding: ['40px', '0', '20px', '0']

  - block: markdown
    id: digital-transformation
    content:
      title: ''
      text: |
        <div class="research-section">
          <div class="research-image">
            <img src="../media/data_digitalization.jpg" alt="Data Digitalization" style="width: 100%; height: auto; border-radius: 8px;">
          </div>
          <div class="research-text">
            <h2 style="margin-top: 0">Data Digitalization</h2>
            <p>
              Much of the chemical and materials literature remains locked in legacy formats, limiting AI systems' ability to leverage this knowledge. Our research focuses on converting scientific literature into structured, machine-readable forms to enable large-scale aggregation and analysis. Key research foci include: 
              <br><br>
              1) extracting data from scientific graphics,
              <br>
              2) reasoning over multimodal data and inferring missing details, and
              <br>
              3) establishing metrics to assess reproducibility and reusability of digitized data.
              <br><br>
            </p>
          </div>
        </div>
    design:
      columns: '1'

  - block: markdown
    id: electrochemistry
    content:
      title: ''
      text: |
        <div class="research-section">
          <div class="research-image">
            <img src="../media/digitial-electrosynthesis.jpg" alt="Digital Electrosynthesis" style="width: 100%; height: auto; border-radius: 8px;">
          </div>
          <div class="research-text">
            <h2 style="margin-top: 0;">Digital Electrosynthesis</h2>
            <p>
              Organic electrosynthesis offers unique advantages such as enhanced selectivity, higher reactivity, and milder reaction conditions. Yet, reaction discovery still relies heavily on trial-and-error. Our group integrates data-driven and AI-enabled approaches to transform electrosynthesis research. Our efforts span the full research pipeline, from initial discovery and optimization to reactor design and scale-up. Key research areas include: 
              <br><br>
              1) discovering reaction design heuristics at scale,
              <br>
              2) transferring insights from conventional organic synthesis to electrochemical reactions,
              <br>
              3) developing descriptors that capture electrosynthesis conditions for improved model performance; and
              <br>
              4) predicting optimal electrosynthesis reaction conditions.
              <br><br>
            </p>
          </div>
        </div>
    design:
      columns: '1'

  - block: markdown
    id: automation
    content:
      title: ''
      text: |
        <div class="research-section">
          <div class="research-image">
            <img src="../media/self-driving-laboratories.jpg" alt="Mechanism-Guided Self-Driving Laboratories" style="width: 100%; height: auto; border-radius: 8px;">
          </div>
          <div class="research-text">
            <h2 style="margin-top: 0;">Mechanism-Guided Self-Driving Laboratories</h2>
            <p>
              We develop chemistry-aware AI systems to guide rational, mechanism-driven reaction discovery and catalyst design beyond black-box predictions. Focusing on heterogeneous electrocatalysts, our research includes:
              <br><br>
              1) autonomous reasoning over multimodal experimental data, including in operando spectroscopy, electroanalysis, and product characterization, to resolve reaction pathways and kinetics,
              <br>
              2) high-throughput synthesis of model heterogeneous electrocatalysts, such as nanocrystals with tunable surface facets, to study surface-reactivity relationships,
              <br>
              3) development of AI models that perform mechanistic reasoning to generate hypotheses and propose targeted experiments, and
              <br>
              4) development of self-driving laboratories that couple autonomous insight generation with iterative experimental design.
            </p>
          </div>
        </div>
    design:
      columns: '1'

  - block: markdown
    content:
      title: ''
      text: |
        <style>
        .research-section {
          display: grid;
          grid-template-columns: 1fr 1fr;
          gap: 40px;
          align-items: center;
          max-width: 1200px;
          margin: 40px auto;
        }

        .research-text p {
          font-size: 16px;
          line-height: 1.6;
        }

        @media (max-width: 768px) {
          .research-section {
            grid-template-columns: 1fr !important;
            gap: 20px !important;
            margin: 20px auto !important;
          }

          .research-text h2 {
            font-size: 24px !important;
          }

          .research-text p {
            font-size: 15px !important;
          }
        }
        </style>
    design:
      columns: '1'
---
