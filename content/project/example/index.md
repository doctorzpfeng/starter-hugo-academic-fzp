---
title: Visualizing Neural Network
summary:  This project mainly focuses on visualizing CNN in SAR and SEI scenarios.
tags:
  - various CAM for SAR images and time-frequency analysis
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

## XXX

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

This project mainly foucues on visualizing the inner mechanism of artifical neural networks with radar images and signals. Artificial neural networks, especially convolutional
neural networks (CNNs), have obtained remarkable achievements in computer vision, however, there still lacks a clear interpretation of CNN's decision. To alleviate such a "black-box" property of CNN, some visualization methods are developed to highlight the regions of an image, which are responsible for
CNN's decision. They can be further categorized as: perturbation-based, propagation-based (Guided Backprob, Layer-wise Relevance Propagation, Deep Taylor, Integrated Gradient, etc)
and activation-based methods ( (class activation mapping, CAM)).