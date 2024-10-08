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

        ## {{< icon name="shield-alt" pack="fas" >}}**전북대학교에 재학중인 IT정보공학과 이진규입니다!**
        
        #### {{< icon name="hackerrank" pack="fab" >}}웹 해킹 / 네트워크 분야에 관심을 가지고 연구 및 공부하고 있습니다!{{< icon name="network-wired" pack="fas" >}}

        #### **웹 보안**, **취약점 분석**, **시큐어 코딩** 전문가를 꿈꾸며{{< icon name="search" pack="fas" >}}
        
        #### {{< icon name="code" pack="fas" >}}혁신적인 **웹 보안 솔루션 개발**에 열정을 쏟고 있습니다{{< icon name="lock" pack="fas" >}}

        &nbsp;
    design:
      background:
        gradient_start: '#e6d5e6'
        gradient_end: '#c2e9fb'
        text_color_light: false

  - block: slider
    content:
      slides:
      - title: <span style="font-size:70%">👋 시큐어코딩</span>
        content: <span style="font-size:70%">어떠한 웹 해킹 기술도 막아내는...</span>
        align: center
        background:
          image:
            filename: secure.jpg
            filters:
              brightness: 0.4
          position: right
          color: '#000'
      - title: <span style="font-size:70%">웹 취약점 점검 ☕️</span>
        content: <span style="font-size:70%">취약점 점검을 통한 웹 보안 강화....</span>
        align: left
        background:
          image:
            filename: webattack.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
      - title: <span style="font-size:70%">개발</span>
        content: <span style="font-size:70%">완벽한 웹 어플리케이션 개발!</span>
        align: right
        background:
          image:
            filename: dev.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
      - title: <span style="font-size:70%">👋 네트워크 보안</span>
        content: <span style="font-size:70%">'강력한 네트워크단의 보안'</span>
        align: center
        background:
          image:
            filename: network.jpg
            filters:
              brightness: 0.4
          position: right
          color: '#000'
      - title: <span style="font-size:70%">시스템 보안 ☕️</span>
        content: <span style="font-size:70%">어떠한 시스템도 뚫거나 막는..!</span>
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
