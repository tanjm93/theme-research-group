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
        <div style="font-size: 0.9rem;">
        We are a  multidisciplinary research team that works at the interface of chemistry, computer science, data science, artificial intelligence, and automation to develop intelligent, adaptive tools and systems that enable autonomous reaction discovery and informatics.
        </div>

  - block: markdown
    content:
      title: Our Research
      text: |
        <div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 30px; max-width: 1200px; margin: 0 auto;">
          <div style="text-align: center;">
            <a href="tour#digital-transformation">
              <img src="/media/data_digitalization.jpg" alt="Data & Digitalization" style="width: 100%; height: auto; border-radius: 8px; transition: transform 0.3s ease;">
            </a>
          </div>
          <div style="text-align: center;">
            <a href="tour#electrochemistry">
              <img src="/media/digitial-electrosynthesis.jpeg" alt="Digital Electrosynthesis" style="width: 100%; height: auto; border-radius: 8px; transition: transform 0.3s ease;">
            </a>
          </div>
          <div style="text-align: center;">
            <a href="tour#automation">
              <img src="/media/self-driving-laboratories.jpeg" alt="Self-Driving Laboratories" style="width: 100%; height: auto; border-radius: 8px; transition: transform 0.3s ease;">
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
      title: "We are recruiting! 👩‍🔬👨‍🔬"
      text: |
        <div style="text-align: center; font-size: 1.2rem; padding: 20px;">
        We will have open positions for undergraduates, graduate students and postdocs in spring 2026!
        </div>
    design:
      columns: '1'
      background:
        color: '#f0f8ff'
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
        <div style="text-align: center; font-size: 1.2rem; padding: 20px;">Watch this space!</div>
    design:
      columns: '1'
---
