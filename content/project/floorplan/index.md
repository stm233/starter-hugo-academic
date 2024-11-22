---
title: AI Design
summary: Apply the GAN to generate the layout of the furniture in the bedroom, living room, dining room and bath room.
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
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

This project is processing during I worked at B&Q company.

At B&Q, where I previously worked as an Applied Scientist, I built a recommendation system that generated architectural layout suggestions based on user preferences, 
transforming floor plans into 2D matrices and enhancing customer experiences through similarity detection algorithms. 
This experience reinforced my capabilities in ML model development and demonstrated my capacity for impactful AI-driven solutions, 
which I am eager to extend into creating meaningful gameplay experiences.

The first step is to detect the space, scale marks and wall/door/window in floorplan.

![FloorPlan Detection Result](./example2.png)
![FloorPlan Detection Result](./example1.jpg)

Then for each space based on the existing category, we match the top 5 case for consumers.
![FloorPlan Detection Result](./cat.png)
