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
    id: schedule
    content:
      title: 스케쥴은 추후에 공개됩니다
      text: "**국내 및 해외 연사자들의 스피킹 + 조별 고기 회식 & University 데이**"
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  #- block: features
  #  id: features
  #  content:
  #    title: Features
  #    text: Build your site with blocks 🧱
  #    items:
  #      - name: Optimized SEO
  #        icon: magnifying-glass
  #        description: Automatic sitemaps, RSS feeds, and rich metadata take the pain out of SEO and syndication.
  #      - name: Fast
  #        icon: bolt
  #        description: Super fast page load with Tailwind CSS and super fast site building with Hugo.
  #      - name: Easy
  #        icon: sparkles
  #        description: One-click deployment to GitHub Pages. Have your new website live within 5 minutes!
  #      - name: No-Code
  #        icon: code-bracket
  #        description: Edit and design your site just using rich text (Markdown) and configurable YAML parameters.
  #      - name: Highly Rated
  #        icon: star
  #        description: Rated 5-stars by the community.
  #      - name: Swappable Blocks
  #        icon: rectangle-group
  #        description: Build your pages with blocks - no coding required!
  #- block: testimonials
  #  content:
  #    title: ""
  #    text: ""
  #    items:
  #      - name: "Hugo Smith"
  #        role: "Marketing Executive at X"
  #        # Upload image to `assets/media/` and reference the filename here
  #        image: "testimonial-1.jpg"
  #        text: "Awesome, so easy to use and saved me so much work with the swappable pre-designed sections!"
  #  design:
  #    spacing:
  #      # Reduce bottom spacing so the testimonial appears vertically centered between sections
  #      padding: ["6rem", 0, 0, 0]
  #- block: cta-card
  #  content:
  #    title: Build your future-proof website
  #    text: As easy as 1, 2, 3!
  #    button:
  #      text: Get Started
  #      url: https://hugoblox.com/templates/
  #  design:
  #    card:
  #      # Card background color (CSS class)
  #      css_class: "bg-primary-700"
  #      css_style: ""
---
