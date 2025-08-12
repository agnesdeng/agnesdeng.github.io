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
      title: Present
      text: Reading, writing, and teaching my 3-year old about $a + b = b + a$
      filters:
        folders:
          - current-project
    design:
      view: showcase
      fill_image: false
      columns: 1
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
