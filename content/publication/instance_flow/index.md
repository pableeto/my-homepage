---
title: "Video Instance Segmentation by Instance Flow Assembly"
authors:
- Xiang Li*
- Jinglu Wang
- Xiao Li
- Yan Lu
date: "2021-10-20T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Accepted to IEEE Transactions on Multimedia
publication_short: Accepted to TMM

abstract: Instance segmentation is a challenging task aiming at classifying and segmenting all object instances of specific classes. While two-stage box-based methods achieve top performances in the image domain, they cannot easily extend their superiority into the video domain. This is because they usually deal with features or images cropped from the detected bounding boxes without alignment, failing to capture pixel-level temporal consistency. We embrace the observation that bottom-up methods dealing with box-free features could offer accurate spacial correlations across frames, which can be fully utilized for object and pixel level tracking. We first propose our bottom-up framework equipped with a temporal context fusion module to better encode inter-frame correlations. Intra-frame cues for semantic segmentation and object localization are simultaneously extracted and reconstructed by corresponding decoders after a shared backbone. For efficient and robust tracking among instances, we introduce an instance-level correspondence across adjacent frames, which is represented by a center-to-center flow, termed as instance flow, to assemble messy dense temporal correspondences. Experiments demonstrate that the proposed method outperforms the state-of-the-art online methods (taking image-level input) on the challenging Youtube-VIS dataset.

# Summary. An optional shortened abstract.
summary: IEEE Transactions on Multimedia (to appear)

#tags:
#- Source Themes
#featured: true

links:
url_pdf: https://arxiv.org/abs/2110.10599

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

