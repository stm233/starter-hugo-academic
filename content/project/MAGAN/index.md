---
title: MAGAN
summary: We utilize the solutions of Monge–Ampère Partial Differential Equation (MAPDE) as the new loss function of WGAN to make the training process more stable.
tags:
  - generation
date: '2020-05-1T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

#image:
#  caption: Photo by rawpixel on Unsplash
#  focal_point: Smart

links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://space.bilibili.com/174482367?spm_id_from=333.337.0.0
url_code: ''
url_pdf: https://patentimages.storage.googleapis.com/c0/b9/1b/39954adb3d5e2e/US11315343.pdf
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

Generative Adversarial Networks (GANs) suffer from the instability of training because of Optimal Transportation (OT) problems. 
Based on Brenier's Theorem, we converted OT problems into solving the elliptic Monge–Ampère Partial Differential Equation (MAPDE) by utilizing the finite difference method. 
In order to solve n (n > 3) dimensional MAPDE, we improved Neumann boundary conditions and extended a discretization of MAPDE for the numerical solution to enable the optimal map between generators and discriminators. 
The solution of MAPDE was regarded as a new divergence instead of Wasserstein Distance from WGAN. 

We provided several computational examples to demonstrate that the precision was increased by 5.3%. 
Moreover, MAGAN was able to stabilize training with almost no hyperparameter tuning and the convergent speed of MAGAN was 317.2% faster than WGAN-GP on LSUN Bedrooms Database. 
MAGAN also achieved the Inception Score (IS) of 8.7 on CIFAR-10.

