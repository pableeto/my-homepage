---
title: "Deep Inverse Rendering for High-resolution SVBRDF Estimation from an Arbitrary Number of Images"
authors:
- Duan Gao*
- Xiao Li*
- Yue Dong
- Pieter Peers
- Xin Tong (* equal contribution)
date: "2019-07-10T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *SIGGRAPH 2019*
publication_short: In *SIG2019*

abstract: In this paper we present a unified deep inverse rendering framework for estimating the spatially-varying appearance properties of a planar exemplar from an arbitrary number of input photographs, ranging from just a single photograph to many photographs. The precision of the estimated appearance scales from plausible when the input photographs fails to capture all the reflectance information, to accurate for large input sets. A key distinguishing feature of our framework is that it directly optimizes for the appearance parameters in a latent embedded space of spatially-varying appearance, such that no handcrafted heuristics are needed to regularize the optimization. This latent embedding is learned through a fully convolutional auto-encoder that has been designed to regularize the optimization. Our framework not only supports an arbitrary number of input photographs, but also at high resolution. We demonstrate and evaluate our deep inverse rendering solution on a wide variety of publicly available datasets.

# Summary. An optional shortened abstract.
summary: SIGGRAPH 2019

#tags:
#- Source Themes
#featured: true

links:
url_pdf: https://gao-duan.github.io/publications/mvsvbrdf/mvsvbrdf_low_resolution.pdf
url_code: https://github.com/msraig/DeepInverseRendering

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

