---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
image: images/kong.jpg
type: landing

design:
  #\= Default section spacing
  spacing: "6rem"


sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: develop portfolio
        url: uploads/develop_portfolio.pdf
    design:
      css_class: dark
      background:
        color: green
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: slider
    position: center

  - block: markdown
    content:
      title: '📚 projects'
      subtitle: ''
    design:
      columns: '1'
  - block: projectsen

  - block: markdown
    content:
      title: '2024 autumn'
      subtitle: ''
    design:
      columns: '1'
  - block: menuen

  - block: card3en


---
