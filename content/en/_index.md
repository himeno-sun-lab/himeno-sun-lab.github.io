---
# Leave the homepage title empty to use the site title
title:
date: 2024-10-01
type: landing

sections:
  - block: hero
    content:
      title: |
        Himeno-Sun Labouratory
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        **Himeno-Sun Lab** concentrates on artificial intelligence and computing science and its application in medicine field, and computational neuroscience.
        
        And it attempts to be a center of excellence for intelligent medicine and computational neuroscience research, teaching, and practice since its founding in 2022.

  - block: people
    content:
      title: Team Leaders
      user_groups:
        - Principal Investigators
      sort_by: Params.weight
      sort_ascending: true

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
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
