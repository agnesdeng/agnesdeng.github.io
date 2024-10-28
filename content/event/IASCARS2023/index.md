---
title: 'miae: Multiple Imputation Through Autoencoders'

event: The 12th conference of the Asian Regional Section of the International Association for Statistical Computing (IASC-ARS)
event_url: https://iascars2023.netlify.app/

location: Macquarie University, NSW, Australia
address:
  street: Wallumattagal Campus
  city: Sydney
  #region: CA
 # postcode: '94305'
  country: Australia

summary: Demonstrate R package miae. Implemented with Torch.
abstract: 'Standard implementations of multiple imputation have limitations in handling missing data in large datasets with complex data structures. Achieving satisfactory imputation performance often depends on properly specifying the imputation model to account for interactions among variables. Therefore, imputing a large dataset can be daunting, particularly when there is a large number of incomplete variables. In this talk, we will discuss the potential of applying different variants of autoencoders to multiple imputation. A comprehensive analysis on the the effect of hyperparameters on imputation performance is given. We provide insights into the suitability of using autoencoders for multiple imputation tasks and give practical suggestions to improve their imputation performance. The proposed procedure is implemented in an R package miae, which uses torch as the backend, so that setting up Python is not required. In addition, miae aims to provide an automated procedure, where the main imputation function can automatically handle tasks such as data preprocessing and proprocessing, without requiring extra work from users. Various statistical techniques have also been implemented to enhance the imputation performance of miae and its performance is evaluated and compared to those of mice and mixgb. The development version of miae is available at <a href="https://github.com/agnesdeng/miae">https://github.com/agnesdeng/miae</a>.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2023-12-07T13:30:00Z'
date_end: '2023-12-07T15:10:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2023-11-01T00:00:00Z'

authors:
  - admin

tags:
  - miae
  - Autoencoders
  - Multiple Imputation

# Is this a featured talk? (true/false)
featured: false

image:
  #caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
url_code: 'https://github.com/agnesdeng/miae'
#url_pdf: ''
#url_slides: ''
#url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---


