---
title: 'Multiple imputation through variational  autoencoders'

event: New Zealand Statistical Association 2019 Conference
event_url: https://www.otago.ac.nz/nzsa

location: University of Otago, New Zealand
address:
  street: 362 Leith Street
  city: Dunedin
  #region: CA
 # postcode: '94305'
  country: New Zealand

summary: Implemented with TensorFlow.
abstract: 'Missing values are ubiquitous in clinical and social science data. Incomplete data not only leads to loss of information but can also introduce bias, which poses a significant challenge for data analysis. Various imputation procedures were designed to handle incomplete data under different missingness mechanisms. Rubin (1977) introduced multiple imputation to attain valid inference from data with ignorable nonresponse. Some techniques and R packages are developed to implement multiple imputations, such as MICE, Amelia and MissForest. However, the running time of imputation using these methods can be excessive for large datasets. We propose a scalable multiple imputation method based on variational and denoising autoencoders.  Our R package mivae is built using the tensorflow package in R, which enables fast computation and thus provides a scalable solution for missing data.  In this presentation, I will demonstrate some features of the R package mivae and compare the performance of several commonly used multiple imputation techniques.  Multiple imputation inference will also be discussed. '

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2019-11-26T13:00:00Z'
date_end: '2019-11-28T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags:
  - Multiple Imputation
  - Autoencoders

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
url_code: 'https://github.com/agnesdeng/misle'
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


