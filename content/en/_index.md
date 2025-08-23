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
      title: Bitcoin Mini Conference
      text: 🚀 SECOND EDITION OF THE BITCOIN MINI CONFERENCE 🚀
      primary_action:
        text: Get Tickets in BTC
        url: https://store.btcmap.kr/meetup/Bitcoin_Mini_Conference/11/
        icon: rocket-launch
      secondary_action:
        text: See Speakers
        url: /#speakers
      announcement:
        text: "November 29-30"
        link:
          text: "Buy tickets in KRW"
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
            Attendees in 2024
        - statistic: "1st"
          description: |
            Community led conference in Korea
        - statistic: "400+"
          description: |
            Expected attendees in 2025
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: people
    id: speakers
    content:
      title: Speakers
      text: ""
      user_groups: ['Speakers']
    design:
      show_role: true
      show_social: true
  - block: markdown
    id: more-spakers
    content:
      title: More speakers on the way!
  - block: cta-image-paragraph
    id: schedule
    content:
      items:
        - title: "First day: Curated talks to deliver maximum signal-to-noise ratio."
          text: A single stage with insightful talks prepared by industry leading experts. K-BBQ dinner provided afterwards to all attendees to strengthen relationships between community members.
          image: nsp-cropped.JPG

        - title: "Second day: Hands on workshops with a Lightning Market in the heart of Seoul"
          text: Workshops with a maximum size of 30 people to provide the attendees with quality educational sessions. Booths in the form of a Lightning market in the streets of Seoul to allow access for everyone in Seoul to visit and become a part of the community.
          image: spaceb.png
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: logos
    content:
      title: "Sponsors"
      # Image path relative to assets/media/ folder
      logo_folder: 'sponsors/'
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
