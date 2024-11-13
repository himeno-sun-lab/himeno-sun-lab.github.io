---
# Leave the homepage title empty to use the site title
title:
date: 2024-10-01
type: landing

sections:
  - block: hero
    content:
      title: |
        姫野・孫研究室
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        **姫野・孫研究室** は人工知能と計算科学、特に医療分野や計算神経科学への応用に取り組んでいます。
        
        2022年の設立以来、知的医療と計算神経科学の研究・教育・実践における卓越した研究拠点を目指しています。

  - block: people
    content:
      title: チームリーダー
      user_groups:
        - 主任研究者
      sort_by: Params.weight
      sort_ascending: true

  - block: collection
    content:
      title: 最新ニュース
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
          filename: yamanakako.jpg
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
      title: 最新プレプリント
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
