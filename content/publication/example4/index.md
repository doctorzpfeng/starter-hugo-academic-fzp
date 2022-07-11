---
title: 'Analytical Interpretation of Latent Codes in InfoGAN with SAR Images'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Milos Dakovic
  - Hongbing Ji
  - Mingzhe Zhu
  - Ljubisa Stankovic

# Author notes (optional)
author_notes:
  - 'First Author and Corresponding Author'


date: '2022-05-27T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-05-27T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *arXiv*
publication_short: In *arXiv*

abstract: Generative Adversarial Networks (GANs) can synthesize abundant photo-realistic synthetic aperture radar (SAR) images. Some recent GANs (e.g., InfoGAN), are even able to edit specific properties of the synthesized images by introducing latent codes. It is crucial for SAR image synthesis since the targets in real SAR images are with different properties due to the imaging mechanism. Despite the success of InfoGAN in manipulating properties, there still lacks a clear explanation of how these latent codes affect synthesized properties, thus editing specific properties usually relies on empirical trials, unreliable and time-consuming. In this paper, we show that latent codes are disentangled to affect the properties of SAR images in a non-linear manner. By introducing some property estimators for latent codes, we are able to provide a completely analytical nonlinear model to decompose the entangled causality between latent codes and different properties. The qualitative and quantitative experimental results further reveal that the properties can be calculated by latent codes, inversely, the satisfying latent codes can be estimated given desired properties. In this case, properties can be manipulated by latent codes as we expect.

# Summary. An optional shortened abstract.
# summary: 
tags: []

# Display this page in the Featured widget?
featured: false

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
