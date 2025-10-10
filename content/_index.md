---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
         LEONG Research Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        <div style="font-size: 1rem;">
        We are a  multidisciplinary research team at Nanyang Technological University's School of Chemistry, Chemical Engineering and Biotechnology (NTU, CCEB) in Singapore. We work at the interface of chemistry, computer science, data science, artificial intelligence, and automation to develop intelligent, adaptive tools and systems that enable autonomous reaction discovery and informatics.
        </div>

  - block: markdown
    content:
      title: Our Research
      text: |
        <div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 30px; max-width: 1200px; margin: 0 auto;">
          <div style="text-align: center;">
            <a href="research#digital-transformation" style="position: relative; display: block;">
              <img src="media/data_digitalization.jpg" alt="Data Digitalization" style="width: 100%; height: auto; border-radius: 8px; transition: transform 0.3s ease;">
              <div style="position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); color: white; font-size: 1rem; font-weight: bold; text-shadow: 2px 2px 8px rgba(0,0,0,0.8); white-space: nowrap;background: rgba(0,0,0,0.5); padding: 1px 10px;">
                Data Digitalization
              </div>
            </a>
          </div>
          <div style="text-align: center;">
            <a href="research#electrochemistry" style="position: relative; display: block;">
              <img src="media/digitial-electrosynthesis.jpg" alt="Digital Electrosynthesis" style="width: 100%; height: auto; border-radius: 8px; transition: transform 0.3s ease;">
              <div style="position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); color: white; font-size: 1rem; font-weight: bold; text-shadow: 2px 2px 8px rgba(0,0,0,0.8); white-space: nowrap; background: rgba(0,0,0,0.5); padding: 1px 10px;">
                Digital Electrosynthesis
              </div>
            </a>
          </div>
          <div style="text-align: center;">
            <a href="research#automation" style="position: relative; display: block;">
              <img src="media/self-driving-laboratories.jpg" alt="Mechanism-Guided Self-Driving Laboratories" style="width: 100%; height: auto; border-radius: 8px; transition: transform 0.3s ease;">
              <div style="position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); color: white; font-size: 1rem; font-weight: bold; text-shadow: 2px 2px 8px rgba(0,0,0,0.8); text-align: center; background: rgba(0,0,0,0.5); padding: 1px 10px; width: 95%; line-height: 1.2;">
                Mechanism-Guided Self-Driving Laboratories
              </div>
            </a>
          </div>
        </div>

        <style>
        @media (max-width: 768px) {
          div[style*="grid-template-columns"] {
            grid-template-columns: 1fr !important;
          }
        }
        a img:hover {
          transform: scale(1.05);
        }
        </style>
    design:
      columns: '1'

  - block: markdown
    content:
      title: "We are recruiting! 👩🏻‍🔬🧑🏻‍🔬"
      text: |
        <div style="text-align: center; font-size: 1rem; padding: 20px;">
        We're recruiting graduate students for the Aug 2026 intake. We also welcome applications from undergraduate researchers and postdocs to start as early as spring 2026! Learn more <a href="contact">here</a>! 
        </div>
    design:
      columns: '1'
      background:
        color: 
      spacing:
        padding: ['30px', '0', '30px', '0']

  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  # - block: collection
  #   content:
  #     title: Latest Preprints
  #     text: ""
  #     count: 5
  #     filters:
  #       folders:
  #         - publication
  #       publication_type: 'article'
  #   design:
  #     view: citation
  #     columns: '1'

  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: '1'

  - block: markdown
    content:
      title: Latest Publications
      subtitle:
      text: |
        <div style="text-align: center; font-size: 1rem; padding: 20px;">Watch this space!</div>
    design:
      columns: '1'
---
