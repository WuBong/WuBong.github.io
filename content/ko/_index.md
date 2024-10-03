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
  - block: custom
    content: |
      <div class="slider">
          <div class="slides">
              <input type="radio" name="radio" id="slide1" checked>
              <input type="radio" name="radio" id="slide2">
              <input type="radio" name="radio" id="slide3">
              
              <div class="slide s1">
                  <img src="/images/unity.jpg" alt="Slide 1">
              </div>
              <div class="slide">
                  <img src="/images/rock.jpg" alt="Slide 2">
              </div>
              <div class="slide">
                  <img src="/images/directx.jpg" alt="Slide 3">
              </div>
              
              <div class="navigation">
                  <label for="slide1"></label>
                  <label for="slide2"></label>
                  <label for="slide3"></label>
              </div>
          </div>
      </div>

      <style>
          /* 슬라이더 CSS 스타일 */
          .slider {
              position: relative;
              max-width: 800px;
              margin: auto;
              overflow: hidden;
          }
          .slides {
              display: flex;
              transition: transform 0.5s ease-in-out;
          }
          .slide {
              min-width: 100%;
              box-sizing: border-box;
          }
          .slide img {
              width: 100%;
          }
          input[type="radio"] {
              display: none;
          }
          #slide1:checked ~ .slides {
              transform: translateX(0%);
          }
          #slide2:checked ~ .slides {
              transform: translateX(-100%);
          }
          #slide3:checked ~ .slides {
              transform: translateX(-200%);
          }
          .navigation {
              position: absolute;
              bottom: 10px;
              left: 50%;
              transform: translateX(-50%);
              display: flex;
          }
          .navigation label {
              background: #fff;
              border: 1px solid #ccc;
              border-radius: 50%;
              width: 10px;
              height: 10px;
              margin: 0 5px;
              cursor: pointer;
          }
      </style>

      <script>
          // 추가적인 JavaScript가 필요하다면 여기에 작성
      </script>
---
