---
title: 'Project'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: collection
    content:
      title: Current Projects
      text: What I'm working on now.
      filters:
        folders:
          - current-project
    design:
      view: article-grid
      fill_image: false
      columns: 3
  - block: collection
    content:
      title: Past Projects
      text: These are the R packages that I made during my PhD. 
      filters:
        folders:
          - past-project
    design:
      view: article-grid
      fill_image: false
      columns: 3
---
