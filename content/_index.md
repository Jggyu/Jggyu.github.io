---
title: 'Home'
date: 2023-10-24
type: landing
design:
  background:
    image:
      # Add your image background to `assets/media/`.
      filename: bg-hue.svg
sections:
  - block: resume-biography
    content:
      # The user's folder name in content/authors/
      username: admin
    design:
      biography:
        style: 'text-align: justify; font-size: 0.8em;'

  - block: slider
    content:
      slides:
      - title: <span style="font-size:70%">Recruit</span>
        content: <span style="font-size:70%">Interested in MacsLAB?</span>
        align: center
        background:
          image:
            filename: recruitment.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: user
          icon_pack: fas
          text: <span style="font-size:60%">Join Us</span>
          text-color: '#000'
          url: contact

      - title: <span style="font-size:70%">AI</span>
        content: <span style="font-size:70%">의료/항공우주/컨텐츠 등 특성화 분야에 적용 가능한 AI 기술 개발<span style="font-size:70%">
        align: center
        background:
          image:
            filename: Ai.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Healthcare</span>
        content: <span style="font-size:70%">의료 및 헬스케어 분야에 적용 가능한 AI 기술 개발</span>
        align: center
        background:
          image:
            filename: healthcare.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Mathematics</span>
        content: <span style="font-size:70%">AI와 관련된 수학 및 최적화 이론 연구</span>
        align: center
        background:
          image:
            filename: mathematics.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Development</span>
        content: <span style="font-size:70%">기반 기술을 활용한 Full-Stack 어플리케이션 개발</span>
        align: center
        background:
          image:
            filename: development.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      slide_width: '100px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000

  - block: cta-button-list
    content:
      # Need a custom icon?
      # Add an SVG image to the `assets/media/icons/` folder and reference it in the `icon` field below
      buttons:
        - text: Read my latest paper on LLMs
          icon: academicons/arxiv
          url: https://arxiv.org/abs/2304.01852
        - text: Watch my new YouTube video to achieve 20x productivity
          icon: brands/youtube
          url: https://youtube.com
        - text: Connect with me on LinkedIn
          icon: brands/linkedin
          url: https://linkedin.com

  - block: collection
    content:
      id: section-1
      title: "Notifications"
      subtitle: ""
      text: ""
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - about
          - experience
    design:
      view: community/custom_card
      columns: '3'

  - block: collection
    content:
      id: section-2
      title: card test2
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - about
          - experience
    design:
      view: community/custom_card
      columns: '2'

  - block: collection
    content:
      id: section-3
      title: card test3
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - about
          - experience
    design:
      view: community/custom_card
      columns: '2'
---