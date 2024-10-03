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
        - title: 👋 Welcome to the group
          content: Take a look at what we're working on...
          align: center
          background:
            position: right
            color: '#666'
            brightness: 0.7
            media: Ai.jpg
            fit: cover
        - title: Lunch & Learn ☕️
          content: 'Share your knowledge with the group and explore exciting new topics together!'
          align: left
          background:
            position: center
            color: '#555'
            brightness: 0.7
            media: recruitment.jpg
            fit: cover
        - title: World-Class Semiconductor Lab
          content: 'Just opened last month!'
          align: right
          background:
            position: center
            color: '#333'
            brightness: 0.5
            media: mathematics.jpg
            fit: cover
          link:
            icon: graduation-cap
            icon_pack: fas
            text: Join Us
            url: '../contact/'
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000

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