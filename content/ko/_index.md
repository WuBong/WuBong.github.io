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
  - block: slider  # 슬라이더 블록 추가
    content:
      slides:
        - title: <span style="font-size:90%">game</span>
          content: <span style="font-size:90%">게임 개발</span>
          align: center
          background:
            image:
              filename: images/unity.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'

        - title: <span style="font-size:90%">graphics </span>
          content: <span style="font-size:90%">다이렉트X</span>
          align: center
          background:
            image:
              filename: images/directx.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'

        - title: <span style="font-size:90%">music</span>
          content: <span style="font-size:90%">J-rock, J-pop</span>
          align: center
          background:
            image:
              filename: images/rock.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'
---