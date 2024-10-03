---
# 슬라이더 위젯
widget: slider
# 이 위젯이 표시될 순서 (낮은 숫자가 먼저 표시됨)
weight: 1
# 이 섹션을 활성화할지 여부
active: true
# 이 파일이 페이지 섹션을 나타냄
headless: true

# 슬라이더 설정
design:
  # 슬라이드 높이 (예: '400px', 기본값: auto)
  slide_height: ''
  is_fullscreen: true
  # 슬라이드 자동 전환 여부
  loop: false
  # 슬라이드 전환 간격 (밀리초)
  interval: 2000

# 슬라이드 내용
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
        media: healthcare.jpg
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
        url: ../contact/
---