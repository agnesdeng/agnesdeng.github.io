---
title: 'Multiple Imputation Through XGBoost'
authors:
- admin
- Thomas Lumley
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2023-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Computational and Graphical Statistics, 33*(2), 352–363"
publication_short: ""

abstract: The use of multiple imputation (MI) is becoming increasingly popular for addressing missing data. Although some conventional MI approaches have been well studied and have shown empirical validity, they have limitations when processing large datasets with complex data structures. Their imputation performances usually rely on the proper specification of imputation models, and this requires expert knowledge of the inherent relations among variables. Moreover, these standard approaches tend to be computationally inefficient for medium and large datasets. In this paper, we propose a scalable MI framework mixgb, which is based on XGBoost, subsampling, and predictive mean matching. Our approach leverages the power of XGBoost, a fast implementation of gradient boosted trees, to automatically capture interactions and nonlinear relations while achieving high computational efficiency. In addition, we incorporate subsampling and predictive mean matching to reduce bias and to better account for appropriate imputation variability. The proposed framework is implemented in an R package mixgb. Supplementary materials for this article are available online.

# Summary. An optional shortened abstract.
summary:  A faster multiple imputation approach that yields reliable results.

tags:
- mixgb
- Multiple Imputation

featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://www.tandfonline.com/doi/full/10.1080/10618600.2023.2252501
url_code: 'https://github.com/agnesdeng/mixgb-supplement'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  #caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
 **Full text** of this paper
{{% /callout %}}

[Multiple Imputation Through XGBoost](https://www.tandfonline.com/doi/full/10.1080/10618600.2023.2252501)

{{% callout note %}}
**Supplementary materials** of this paper
{{% /callout %}}

[Github repository](https://github.com/agnesdeng/mixgb-supplement)

