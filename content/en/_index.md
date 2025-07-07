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
        text: Get Tickets
        url: https://store.btcmap.kr/meetup/Bitcoin_Mini_Conference/7/
        icon: rocket-launch
      secondary_action:
        text: See Speakers
        url: /#speakers
      announcement:
        text: "November 29-30"
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
        - statistic: "300+"
          description: |
            Expected attendees in 2025
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: markdown
    id: speakers
    content:
      title: Speakers to be announced soon!
      text: "**20+ speakers & 10+ workshops!**"
  - block: markdown
    id: schedule
    content:
      title: Schedule to be announced soon!
      text: "**1 full day of talks+dinner & 1 full day of workshops!**"
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
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
---
