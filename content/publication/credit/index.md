---
title: 3DACN: 3D Augmented Convolutional Network for Time Series Data
authors:
- Songwen Pei
- Tianma Shen
- Chunhua Gu
- Bingxue Zhang
- Zhong Ning
- Naixue Xiong


#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2019-01-12T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-01-12T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Information Sciences*"
publication_short: ""

abstract: Time series data and non-time series data is increasing in the credit system of financial market, so that an effective and intellegent data mining model plays a critical role to analyze big data. We propose a three dimensional and augmented convolutional network (3DACN) to extract the value concatenation with time series information from the parallel structure of GRUs and FCs. For hybrid time series data, there are much more samples in a specific class, and the ratio is up to 93.1\%. Thus, the serious imbalanced problem causes the algorithm failing to converge. Due to the imbalanced problem, it's necessary to enhance the 3D convolutional network by an augmented algorithm on time series data. 3DACN ensures the latent variables with an Expectation-maximization algorithm to improve F1 score (F1) and Area Under Curve (AUC). Experimental results show that in the benchmark of credit risk database, the 3DACN can reach a high performance on F1 up to 88.1\% and the AUC up to 88.4\%; while in the benchmark of bank database up to 81.1\%, 88.2\% respectively.   

  
# Summary. An optional shortened abstract.
summary: In this paper, we propose 3D Augmented Convolutional Network(3DACN) for hybird time series data by setting three dimensionsy to make convolutions along time dimension and use augmented algorithm and EM algorithm to solve imbalanced data problem and extract the value concatenation containing time series information respectivly. We verified the 3DACN on two Databases and got better performance of F1 score and AUC than other algorithms. According to the result of F1 score and AUC, we can prove our 3DACN having a strong ability to deal with hybird time series data including imbalance data.


tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#  focal_point: ""
#  preview_only: false

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
slides: ''
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
