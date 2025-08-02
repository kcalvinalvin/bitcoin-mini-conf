---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: 비트코인 미니 컨퍼런스
      text: 🚀 2025년에도 다시 돌아온 비트코인 미니 컨퍼런스 🚀
      primary_action:
        text: "원화로 티켓 구매하기"
        url: https://smartstore.naver.com/promenadecastle/products/12055415750
        icon: rocket-launch
      secondary_action:
        text: 연사 보기
        url: /#speakers
      announcement:
        text: "11월 29-30일"
        link:
          text: 비트코인으로 티켓 구매하기
          url: https://store.btcmap.kr/meetup/Bitcoin_Mini_Conference/11/
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: background-4.jpg
          filters:
            brightness: 0.5
  - block: stats
    content:
      items:
        - statistic: "200+"
          description: |
            2024년에 참여한 분들
        - statistic: "국내 유일"
          description: |
            비트코인 커뮤니티가 주최하는 컨퍼런스
        - statistic: "300+"
          description: |
            2025년 예상 참여자
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: people
    id: speakers
    content:
      title: 연사
      text: ""
      user_groups: ['Speakers']
    design:
      show_role: true
      show_social: true
  - block: markdown
    id: more-spakers
    content:
      title: "연사자는 계속 발표됩니다!"
  - block: cta-image-paragraph
    id: about
    content:
      items:
        - title: Main Day
          text: 비트코인의 이해도가 높고 인사이트가 있는 사람들로 엄선하여 모두 함께 강연 형식으로 컨퍼런스를 즐기실 수 있습니다. 행사가 마무리 된 이후에는 참석자끼리의 교류를 활성화 하기 위해 모든 참여자분들께 소고기 회식을 제공합니다.
          image: nsp-cropped.JPG

        - title: Uni Day
          text: 만나기 어렵던 진짜 전문가들과 함께 심층 높은 지식을 강의 형식으로 빠르게 배워갈 수 있습니다. 별도의 라이트닝 마켓 공간에서는 다양한 비트코인 관련 물건들을 만나보고 비트코인으로 구매하실 수 있습니다.
          image: resone.JPG

    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
---
