---
title: "A system for tracking whisker kinematics and whisker shape in three dimensions"
authors:
- Rasmus Petersen
- Andrea Colins
- Mathew Evans
- Dario Campagner
- Michaela Loft

date: "2020-02-010T00:00:00Z"
doi: "https://doi.org/10.1101/773697"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
# publication: "Plos Comp Biol  **12**, e0169601 (2017)"


abstract: Quantification of behaviour is essential for systems neuroscience. Since the whisker system is a major model system for investigating the neural basis of behaviour, it is important to have methods for measuring whisker movements from behaving animals. Here, we developed a high-speed imaging system that measures whisker movements simultaneously from two vantage points. We developed an algorithm that uses the ‘stereo' video data to track multiple whiskers by fitting 3D curves to the basal section of each target whisker. By using temporal information to constrain the fits, the algorithm is able to track multiple whiskers in parallel with low error rate. We used the output of the tracker to produce a 3D description of each tracked whisker, including its 3D orientation and 3D shape, as well as bending-related mechanical force. In conclusion, we present an automatic system to track whiskers in 3D from high-speed video, creating the opportunity for comprehensive 3D analysis of sensorimotor behaviour and its neural basis. Author summary The great ethologist Niko Tinbergen described a crucial challenge in biology to measure the “total movements made by the intact animal”. Advances in high-speed video and machine analysis of such data have made it possible to make profound advances. Here, we target the whisker system. The whisker system is a major experimental model in neurobiology and, since the whiskers are readily imageable, the system is ideally suited to machine vision. Rats and mice explore their environment by sweeping their whiskers to and fro. It is important to measure whisker movements in 3D, since whiskers move in 3D and since the mechanical forces that act on them are 3D. However, the problem of automatically tracking whiskers in 3D from video has generally been regarded as prohibitively difficult. Our innovation here is to extract 3D information about whiskers using a two-camera, high-speed imaging system and to develop computational methods to infer 3D whisker state from the imaging data. Our hope is that this study will facilitate comprehensive, 3D analysis of whisker behaviour and, more generally, contribute new insight into brain mechanisms of perception and behaviour.

# Summary. An optional shortened abstract.
# summary: Plos One **12**, e0169601 (2017)

tags:
- Behaviour
- Neuroscience
- Whisker system



links:
 - name: "bioRxiv"
   url: "https://www.biorxiv.org/content/10.1101/773697v1"
# url_pdf: 
 - name: "github"
   url_code: "https://www.github.com/PetersenLab/WhiskerMan"
 - name: "data"  
   url_dataset: "http://www.doi.org/10.6084/m9.figshare.9758894"
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

featured: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image: "featured.png"
#  caption: "Figure 4"
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
