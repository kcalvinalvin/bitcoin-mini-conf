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
        text: 비트코인으로 티켓 구매하기
        url: https://store.btcmap.kr/meetup/Bitcoin_Mini_Conference/7/
        icon: rocket-launch
      secondary_action:
        text: 연사 보기
        url: /#speakers
      announcement:
        text: "11월 29-30일"
        link:
          text: "원화로 티켓 구매하기"
          url: https://smartstore.naver.com/promenadecastle/products/12055415750
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
  - block: markdown
    id: schedule
    content:
      title: 스케쥴은 추후에 공개됩니다
      text: "**국내 및 해외 연사자들의 스피킹 + 조별 고기 회식 & University 데이**"
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
---
