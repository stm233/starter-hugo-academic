---
title: Learned Image Compression with Transformers

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Tianma Shen
  - Ying Liu

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2023-05-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-05-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Big Data V, Learning, Analytics, and Applications*
publication_short: In *Big Data V*

abstract: Recent years have witnessed great advances in deep learning-based image compression, also known as learned image compression. An accurate entropy model is essential in learned image compression, since it can compress high-quality images with a lower bit rate. Current learned image compression schemes developed entropy models using context models and hyperpriors. Context models utilize local correlations within latent representations for better probability distribution approximation, while hyperpriors provide side information to estimate distribution parameters. Most recently, several transformer-based learned image compression algorithms have emerged and achieved state-of-the-art rate distortion performances, surpassing existing convolutional neural network (CNN)-based learned image compression and traditional image compression. Transformers are better at modeling long-distance dependencies and extracting global features than CNNs. However, the research of transformer-based image compression is still in its early stage. In this work, we propose a novel transformer-based learned image compression model. It adopts transformer structures in the main image encoder and decoder and in the context model. In particular, we propose a transformer-based spatial-channel auto-regressive context model. Encoded latent-space features are split into spatial-channel chunks, which are entropy encoded sequentially in a channel-first order, followed by a 2D zigzag spatial order, conditioned on previously decoded feature chunks. To reduce the computational complexity, we also adopt a sliding window to restrict the number of chunks participating in the entropy model. Experimental studies on public image compression datasets demonstrate that our proposed transformer-based learned image codec outperforms traditional image compression and existing learned image compression models visually and quantitatively.
  
# Summary. An optional shortened abstract.
summary: In this paper, we propose a novel learning-based image coding system using transformer structures. Our context model codes latent representations in a channel-first order, followed by a 2D zigzag spatial order. Along with transformer structures, such context model more effectively extracts contextual information for better entropy coding. Further, we propose a transformer-based latent residual cross-attention prediction (LRCP) module to reduce the quantization error.  Compared to existing learned image compression approaches and traditional image compression methods, our proposed model achieved significantly better perceptual quality and RD performance. 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/stm233/image-compression-with-swin-transformer'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - Image/Video Compression

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

