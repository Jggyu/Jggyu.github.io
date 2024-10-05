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
        Lee Jin Gyu is an undergraduate student studying Security at Jeonbuk National University. 
        His research focuses on web security, web vulnerability analysis, and secure coding. 
        He is deeply interested in improving web security through these areas and is actively conducting research on related topics.
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
      - title: 👋 Secure Coding
        content: 'Blocks any web hacking technology...'
        align: center
        background:
          image:
            filename: secure.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: Web vulnerability check ☕️
        content: 'Strengthening web security through vulnerability checking....!'
        align: left
        background:
          image:
            filename: webattack.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: development
        content: 'Perfect web application development!'
        align: right
        background:
          image:
            filename: dev.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
      - title: 👋 Network Security
        content: 'Strong network security'
        align: center
        background:
          image:
            filename: network.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: System Security ☕️
        content: 'Breaking through or blocking any system..!'
        align: center
        background:
          image:
            filename: system.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'  
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: contact
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      slide_width: '100px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000

  - block: collection
    content:
      title: IT Project
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
      page_type: itproject
    design:
      view: community/custom_card
      columns: '1'

  - block: collection
    content:
      title: WEB Project
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
      page_type: webproject
    design:
      view: community/custom_card2
      columns: '1'

  - block: collection
    content:
      title: WEB Project
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
      page_type: study
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
