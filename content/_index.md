---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-04-08
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
  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publications
    design:
      view: community/paper
  - block: collection
    id: projects
    content:
      title: Selected Projects
      filters:
        folders:
          - projects
    design:
      view: article-grid
      fill_image: false
      columns: 2
---
