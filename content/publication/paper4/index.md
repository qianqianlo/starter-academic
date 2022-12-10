---
title: "Learning Robust Agents for Visual Navigation in Dynamic Environments: The Winning Entry of iGibson Challenge 2021"
authors:
- Naoki Yokoyama
- admin
- Dhruv Batra
- Sehoon Ha
author_notes:
- "Equal contribution"
- "Equal contribution"
# date: "2013-07-01T00:00:00Z"
# date: ""
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"
# publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
# publication: In *Source Themes Conference*
# publication_short: In *STC*

abstract: This paper presents an approach for improving navigation in dynamic and interactive environments, which won the 1st place in the iGibson Interactive Navigation Challenge 2021. While the last few years have produced impressive progress on PointGoal Navigation in static environments, relatively little effort has been made on more realistic dynamic environments. The iGibson Challenge proposed two new navigation tasks, Interactive Navigation and Social Navigation, which add displaceable obstacles and moving pedestrians into the simulator environment. Our approach to study these problems uses two key ideas. First, we employ large-scale reinforcement learning by leveraging the Habitat simulator, which supports high performance parallel computing for both simulation and synchronized learning. Second, we employ a new data augmentation technique that adds more dynamic objects into the environment, which can also be combined with traditional image-based augmentation techniques to boost the performance further. Lastly, we achieve sim-to-sim transfer from Habitat to the iGibson simulator, and demonstrate that our proposed methods allow us to train robust agents in dynamic environments with interactive objects or moving humans.
# Summary. An optional shortened abstract.
summary: We train robust agents to navigate in dynamic environments with interactive objects or moving humans, which won the 1st place in the iGibson Interactive Navigation Challenge 2021. 
# tags:
# - Source Themes
featured: true

links:
- name: arXiv
  url: https://arxiv.org/pdf/2109.10493.pdf
# url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
url_video: https://www.youtube.com/watch?v=HxUX2HeOSE4

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
