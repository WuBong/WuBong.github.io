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
---
{{< rawhtml >}}
<div class="card-container">
    <!-- 카드 1 -->
    <div class="card">
        <img src="https://via.placeholder.com/300x150" alt="Card Image 1">
        <div class="card-content">
            <h2 class="card-title">Card Title 1</h2>
            <p class="card-description">This is a description of the first card.</p>
            <a href="#" class="card-button">Read More</a>
        </div>
    </div>

    <!-- 카드 2 -->
    <div class="card">
        <img src="https://via.placeholder.com/300x150" alt="Card Image 2">
        <div class="card-content">
            <h2 class="card-title">Card Title 2</h2>
            <p class="card-description">This is a description of the second card.</p>
            <a href="#" class="card-button">Read More</a>
        </div>
    </div>
</div>
{{< /rawhtml >}}
