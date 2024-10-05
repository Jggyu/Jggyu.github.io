---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing
design:
      background:
        gradient_start: '#e6d5e6'
        gradient_end: '#c2e9fb'
        text_color_light: false


sections:
  - block: about.avatar
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: |
        # 안녕하세요, 전북대학교 IT정보공학과 이진규입니다.

        ## 🔒 전문 분야

        저는 **정보보안**의 세계에 깊이 매료되어 있으며, 특히 다음 분야에 집중하고 있습니다:

        - 🛡️ 시큐어 코딩
        - 🕵️‍♂️ 웹 취약점 분석 및 대응
        - 🔍 침투 테스팅
        
        ## 🎯 현재 연구 중점

        현재 저는 **웹 애플리케이션 보안**에 중점을 두고 연구를 진행 중이며, 특히 *최신 공격 기법에 대한 방어 전략 개발*에 주력하고 있습니다.

        ## 🚀 목표

        1. 혁신적인 웹 보안 솔루션 개발
        2. 취약점 자동 탐지 시스템 구축
        3. 보안 인식 제고를 위한 교육 프로그램 설계

        {{< callout note >}}
        "보안은 단순한 기술이 아닌, 우리 모두의 책임입니다. 저는 이 신념을 바탕으로 더 안전한 디지털 세상을 만들어가고자 합니다."
        {{< /callout >}}

        ## 💡 최근 관심사

        이러한 분야를 통한 웹 보안 향상에 깊은 관심을 갖고 있으며, 관련 주제에 대한 연구를 활발히 진행 중입니다. 특히, 최근에는 **최신기술을 활용한 보안 솔루션 개발**에도 관심을 갖고 연구를 확장하고 있습니다.

        ## 🤝 협력과 성장

        앞으로도 끊임없는 학습과 연구를 통해 사이버 보안 분야의 발전에 기여하고자 합니다. 함께 논의하고 성장할 수 있는 기회를 언제나 환영합니다!

        {{< icon name="github" pack="fab" >}}

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
