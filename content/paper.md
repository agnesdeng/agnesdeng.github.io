---
title: 'Paper'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: collection
    content:
      title: Journal Article
      text: 
      filters:
        folders:
          - journal-article
    design:
      view: article-grid
      view: citation
  - block: collection
    content:
      title: Preprint
      text: 
      filters:
        folders:
          - preprint
    design:
      view: article-grid
      view: citation
  - block: collection
    content:
      title: Conference Paper
      text: 
      filters:
        folders:
          - conference-paper
    design:
      view: article-grid
      view: citation
---