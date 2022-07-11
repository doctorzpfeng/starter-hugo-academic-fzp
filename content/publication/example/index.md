---
title: 'Self-Matching CAM: A Novel Accurate Visual Explanation of
CNNs for SAR Image Interpretation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Mingzhe Zhu
  - Ljubisa Stankovic
  - Hongbing Ji

# Author notes (optional)
author_notes:
  - 'First Author'
  - 'Corresponding Author'

date: '2021-05-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-05-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Remote Sensing*
publication_short: In *Remote Sens*

abstract: Synthetic aperture radar (SAR) image interpretation has long been an important but challenging task in SAR imaging processing. Generally, SAR image interpretation comprises complex procedures including filtering, feature extraction, image segmentation, and target recognition, which greatly reduce the efficiency of data processing. In an era of deep learning, numerous automatic target recognition methods have been proposed based on convolutional neural networks (CNNs) due to their strong capabilities for data abstraction and mining. In contrast to general methods, CNNs own an end-to-end structure where complex data preprocessing is not needed, thus the efficiency can be improved dramatically once a CNN is well trained. However, the recognition mechanism of a CNN is unclear, which hinders its application in many scenarios. In this paper, Self-Matching class activation mapping (CAM) is proposed to visualize what a CNN learns from SAR images to make a decision. Self-Matching CAM assigns a pixel-wise weight matrix to feature maps of different channels by matching them with the input SAR image. By using Self-Matching CAM, the detailed information of the target can be well preserved in an accurate visual explanation heatmap of a CNN for SAR image interpretation. Numerous experiments on a benchmark dataset (MSTAR) verify the validity of Self-Matching CAM.


# Summary. An optional shortened abstract.
# summary: 
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
