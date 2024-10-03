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

{{< partial "card1.html" (dict "title" "Project 1" "image" "/images/project1.jpg" "description" "A brief description of Project 1." "button_text" "Learn More" "button_url" "#") >}}

{{< partial "card2.html" (dict "title" "Project 2" "image" "/images/project2.jpg" "description" "A brief description of Project 2." "button_text" "Read More" "button_url" "#") >}}