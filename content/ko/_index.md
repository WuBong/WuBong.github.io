---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
            - block: custom
  - block: custom
    content:
      title: 'Project Cards'
      cards:
        - title: 'Project 1'
          description: 'Description of project 1.'
          image: 'https://via.placeholder.com/300x150'
          button_text: 'View More'
          button_url: '#'
        - title: 'Project 2'
          description: 'Description of project 2.'
          image: 'https://via.placeholder.com/300x150'
          button_text: 'View More'
          button_url: '#'
        - title: 'Project 3'
          description: 'Description of project 3.'
          image: 'https://via.placeholder.com/300x150'
          button_text: 'View More'
          button_url: '#'
    design:
      css_class: 'card-section'
---