---
title: "Single Photograph Surface Appearance Modeling with Self-augmented CNNs and Inexact Supervision"
authors:
- Wenjie Ye
- Xiao Li
- Yue Dong
- Pieter Peers
- Xin Tong
date: "2018-07-10T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Pacific Graphics 2018*
publication_short: In *PG2018*

abstract: We present a deep learning based method for estimating the spatially varying surface reflectance properties from a single image of a planar surface under unknown natural lighting trained using only photographs of exemplar materials without referencing any artist generated or densely measured spatially varying surface reflectance training data. Our method is based on an empirical study of Li et al.'s self-augmentation training strategy that shows that the main role of the initial approximative network is to provide guidance on the inherent ambiguities in single image appearance estimation. Furthermore, our study indicates that this initial network can be inexact (i.e., trained from other data sources) as long as it resolves the inherent ambiguities. We show that the single image estimation network trained without manually labeled data outperforms prior work in terms of accuracy as well as generality.

# Summary. An optional shortened abstract.
summary: Pacific Graphics 2018

#tags:
#- Source Themes
#featured: true

links:
url_pdf: http://www.cs.wm.edu/~ppeers/publications/Ye2018SPS/Ye_CGF2018.pdf
url_code: https://github.com/msraig/InexactSA

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
<!-- 
{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}} -->

<!-- Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->

