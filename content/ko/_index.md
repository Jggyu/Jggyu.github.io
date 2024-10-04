---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: |
        전북대학교 IT정보공학과에 재학중인 이진규라고 합니다. 
        저는 정보보안에 흥미를 느끼며 집중적으로 공부하고 있으며 특히 시큐어코딩, 웹 취약점 점검 등 웹 보안을 중점으로 연구하며 공부하고 있습니다. 
        이러한 분야를 통한 웹 보안 향상에 깊은 관심을 갖고 관련 주제에 대한 연구를 활발히 진행중입니다.
    design:
      background:
        gradient_start: '#e6d5e6'
        gradient_end: '#c2e9fb'
        text_color_light: false
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        .
        
    design:
      columns: '1'
      background:
        gradient_end: '#c2e9fb'
        gradient_start: '#ffffff'
        text_color_light: false
  
  - block: slider
    content:
      slides:
      - title: 👋 시큐어코딩
        content: '어떠한 웹 해킹 기술도 막아내는...'
        align: center
        background:
          image:
            filename: secure.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: 웹 취약점 점검 ☕️
        content: '취약점 점검을 통한 웹 보안 강화....'
        align: left
        background:
          image:
            filename: webattack.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: 개발
        content: '완벽한 웹 어플리케이션 개발!'
        align: right
        background:
          image:
            filename: web2.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 5000

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
