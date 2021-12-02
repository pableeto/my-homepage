---
title: "Modeling Surface Appearance from a Single Photograph using Self-augmented Convolutional Neural Networks"
authors:
- Xiao Li
- Yue Dong
- Pieter Peers
- Xin Tong
date: "2017-07-24T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *SIGGRAPH 2017*
publication_short: In *SIG2017*

abstract: We present a convolutional neural network (CNN) based solution for modeling physically plausible spatially varying surface reflectance functions (SVBRDF) from a single photograph of a planar material sample under unknown natural illumination. Gathering a sufficiently large set of labeled training pairs consisting of photographs of SVBRDF samples and corresponding reflectance parameters, is a difficult and arduous process. To reduce the amount of required labeled training data, we propose to leverage the appearance information embedded in unlabeled images of spatially varying materials to self-augment the training process. Starting from an initial approximative network obtained from a small set of labeled training pairs, we estimate provisional model parameters for each unlabeled training exemplar. Given this provisional reflectance estimate, we then synthesize a novel temporary labeled training pair by rendering the exact corresponding image under a new lighting condition. After refining the network using these additional training samples, we re-estimate the provisional model parameters for the unlabeled data and repeat the self-augmentation process until convergence. We demonstrate the efficacy of the proposed network structure on spatially varying wood, metals, and plastics, as well as thoroughly validate the effectiveness of the self-augmentation training process.

# Summary. An optional shortened abstract.
summary: SIGGRAPH 2017

#tags:
#- Source Themes
#featured: true

links:
url_pdf: https://arxiv.org/abs/1809.00886
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

