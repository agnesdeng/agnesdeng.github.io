---
title: 'Publications'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: collection
    content:
      title: Journal Articles
      text: 
      filters:
        folders:
          - publication/journal-article
    design:
      view: article-grid
      fill_image: false
      view: citation

  - block: collection
    content:
      title: Conference Papers
      text: 
      filters:
        folders:
          - publication/conference-paper
    design:
      view: article-grid
      fill_image: false
      view: citation

  - block: collection
    content:
      title: Preprints
      text: 
      filters:
        folders:
          - publication/preprint
    design:
      view: article-grid
      fill_image: false
      view: citation
---