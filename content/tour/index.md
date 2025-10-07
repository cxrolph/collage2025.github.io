---
title: Tour
date: 2025-10-07

type: landing

sections:
  - block: slider
    content:
      slides:
      - title: 👋 Welcome to the group
        content: Take a look at what we're working on...
        align: center
        background:
          image:
            filename: gynecologist.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      # - title: Lunch & Learn ☕️
      #   content: 'Share your knowledge with the group and explore exciting new topics together!'
      #   align: left
      #   background:
      #     image:
      #       filename: contact.jpg
      #       filters:
      #         brightness: 0.7
      #     position: center
      #     color: '#555'
      - title: 📰 Latest news
        content: |
          <div class="slide-content"> The <span style= "font-weight: bold">COLLAGE team</span> of Galicia recently visited <span style= "font-weight: bold">BCNatal and BCN MedTech</span> in Barcelona to discuss ongoing research. </div>
          <div class="slide-caption">Francisco Avia (Hospital Clinic Barcelona)</div>
        align: left
        background:
          image:
            filename: hospitalclinic.jpeg
            filters:
              brightness: 0.6
          position: center
          color: '#444'
        link:
          text: Read the News
          url: ../post/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
---
