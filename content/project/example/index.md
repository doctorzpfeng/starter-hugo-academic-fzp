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

This project mainly foucues on visualizing the inner mechanism of convolutional neural networks (CNNs) with radar images and signals. CNNs have obtained remarkable achievements in computer vision, however, there still lacks a clear interpretation of CNN's decision. To alleviate such a "black-box" property of CNN, some visualization methods are developed to highlight the regions of an image, which are responsible for
CNN's decision. However, the interpretability of
CNNs is often criticized by the community, as these networks usually look like complicated
black boxes with massive unexplained parameters. Therefore, it is highly desirable
and necessary to find a way to understand and explain what exactly CNNs learned, especially for applications where interpretability is essential (e.g., medical diagnosis,
autonomous driving, and radar signal processing).

An important issue in CNN learning is to explain what CNNs learned from the input to make the correct decision. To this aim, some visualization methods are developed to highlight the regions of an image, which are responsible for
CNN's decision. They can be further categorized as: perturbation-based, propagation-based
and activation-based methods. We mainly concentrate on multiple CAMs due to the excellent performance and efficiency. CAM, originally proposed by B. Zhou, highlights objects by resorting to the activation of feature maps. Numerous modified CAMs are further
proposed, like Grad-CAM, Grad-CAM++, XGrad-CAM, Ablation CAM, and Score-CAM. However, all aforementioned CAMs are based on optical images and none of them show satisfactory effects when applied to SAR images.

In this project, we firstly proposed Self-Matching CAM which is particularly designed for SAR images. The experimental results show that Self-Matching CAM outperforms all current optical-image-based CAMs. Subsequently, we proposed
G-SM-CAM to improve the efficiency of original Self-Matching CAM, whereas G-SM-CAM is at cost of visualization effect. To satisfy both effect and efficiency, we  further proposed SC-SM CAM introducing spectral clustering to split the feature maps with high similarity into the same group. SC-SM CAM performs better and faster than Self-Matching CAM.

Note: Self-Matching CAM and SC-SM CAM are published in Remote Sensing (IF: 5.349) 
          
G-SM-CAM has been published in The 2021 CIE International Conference on Radar (RADAR 2021) and selected as oral paper. The corresponding author Zhenpeng Feng gave the oral presentation on 17, December, 2021.