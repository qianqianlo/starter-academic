---
title: "A Few Shot Adaptation of Visual Navigation Skills to New Observations using Meta-Learning"
authors:
- *admin*
- Maks Sorokin
- Sehoon Ha
# date: "2013-07-01T00:00:00Z"
date: ""
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
publication: In *Source Themes Conference*
publication_short: In *STC*

abstract: Target-driven visual navigation is a challenging problem that requires a robot to find the goal using only visual inputs. Many researchers have demonstrated promising results using deep reinforcement learning (deep RL) on various robotic platforms, but typical end-to-end learning is known for its poor extrapolation capability to new scenarios. Therefore, learning a navigation policy for a new robot with a new sensor configuration or a new target still remains a challenging problem. In this paper, we introduce a learning algorithm that enables rapid adaptation to new sensor configurations or target objects with a few shots. We design a policy architecture with latent features between perception and inference networks and quickly adapt the perception network via meta-learning while freezing the inference network. Our experiments show that our algorithm adapts the learned navigation policy with only three shots for unseen situations with different sensor configurations or different target colors. We also analyze the proposed algorithm by investigating various hyperparameters. 

# Summary. An optional shortened abstract.
summary: We show how vision-based navigation agents can be trained to adapt to new sensor configurations with only a few shots. Rapid adaptation is achieved by introducing a bottleneck between perception and inference networks, and through the perception component's meta-adaptation. 

tags:
- Source Themes
featured: true

# links:
# - name: Custom Link
#  url: http://example.org
# url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
url_arXiv: https://arxiv.org/abs/2011.03609
url_video: https://www.youtube.com/watch?v=3YklCAeBEZY

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
