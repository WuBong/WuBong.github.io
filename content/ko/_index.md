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
  - block: slider
    content:
      slides:

      - title: <span style="font-size:90%">AI</span>
        content: <span style="font-size:90%">게임개발<span style="font-size:90%">
        align: center
        background:
          image:
            filename: images/unity.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:90%">Medical AI</span>
        content: <span style="font-size:90%">그래픽스</span>
        align: center
        background:
          image:
            filename: directx.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:90%">Healthcare</span>
        content: <span style="font-size:90%">J-pop, J-rock</span>
        align: center
        background:
          image:
            filename: rock.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'         
---