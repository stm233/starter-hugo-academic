---
title: Fish2Mesh
summary: 
tags:
  - generation
date: '2020-05-1T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: 'https://fish2mesh.github.io/'

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
This experience reinforced my capabilities in ML model development and demonstrated my capacity for impactful AI-driven solutions.


### Step 1: Floorplan Detection
The initial phase focuses on detecting key elements in the floorplan, including spaces, scale marks, walls, doors, and windows.

Space and Scale Mark Detection: Achieved using a YOLO-based detection model.
Wall, Door, and Window Detection: Handled through a regression network.
Examples of floorplan detection results:
![FloorPlan Detection Result](./example2.png)
![FloorPlan Detection Result](./example1.jpg)

### Step 2: Space Matching and Case Recommendation
For each detected space, we match the top 5 design cases tailored to the consumer's preferences.

Filtering Options: Users can filter recommendations by style and color labels, which are included in our dataset.
Space Matching: To determine the best match, we propose a heatmap of polygon patterns for the floorplan. 
This allows us to compute similarity between each space in the floorplan and spaces in our dataset.
Examples of space matching visualizations:
![FloorPlan Detection Result](./cat.png)
![FloorPlan Detection Result](./heatmap.png)
