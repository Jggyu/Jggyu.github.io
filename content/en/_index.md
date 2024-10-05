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
        &nbsp;

        ## {{< icon name="shield-alt" pack="fas" >}}**This is Jinkyu Lee, majoring in IT and Information Engineering at Chonbuk National University!**
        
        #### {{< icon name="hackerrank" pack="fab" >}}I am researching and studying the web hacking / network field with interest!{{< icon name="network-wired" pack="fas" >}}

        #### Dreaming of becoming an expert in **web security**, **vulnerability analysis**, and **secure coding**{{< icon name="search" pack="fas" >}}
        
        #### {{< icon name="code" pack="fas" >}}We are passionate about developing innovative **web security solutions**{{< icon name="lock" pack="fas" >}}

        &nbsp;
    design:
      background:
        gradient_start: '#e6d5e6'
        gradient_end: '#c2e9fb'
        text_color_light: false
  
  - block: slider
    content:
      slides:
      - title: <span style="font-size:70%">👋 Secure Coding</span>
        content: <span style="font-size:70%">Blocks any web hacking technology...</span>
        align: center
        background:
          image:
            filename: secure.jpg
            filters:
              brightness: 0.4
          position: right
          color: '#000'
      - title: <span style="font-size:70%">Web vulnerability check ☕️</span>
        content: <span style="font-size:70%">Strengthening web security through vulnerability checking....!</span>
        align: left
        background:
          image:
            filename: webattack.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
      - title: <span style="font-size:70%">development</span>
        content: <span style="font-size:70%">Perfect web application development!</span>
        align: right
        background:
          image:
            filename: dev.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
      - title: <span style="font-size:70%">👋 Network Security</span>
        content: <span style="font-size:70%">Strong network security</span>
        align: center
        background:
          image:
            filename: network.jpg
            filters:
              brightness: 0.4
          position: right
          color: '#000'
      - title: <span style="font-size:70%">System Security ☕️</span>
        content: <span style="font-size:70%">Breaking through or blocking any system..!</span>
        align: center
        background:
          image:
            filename: system.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'  
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
      title: Study
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
      subtitle:
      text: |
        {{% cta cta_link="./contact/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
