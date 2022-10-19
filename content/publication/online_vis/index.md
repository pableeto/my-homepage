---
title: "Hybrid Instance-aware Temporal Fusion for Online Video Instance Segmentation"
authors:
- Xiang Li*
- Jinglu Wang
- Xiao Li
- Yan Lu
date: "2021-12-01T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *AAAI 2022*
publication_short: In *AAAI 2022*

abstract: Recently, transformer-based image segmentation methods have achieved notable success against previous solutions. While for video domains, how to effectively model temporal context with the attention of object instances across frames remains an open problem. In this paper, we propose an online video instance segmentation framework with a novel instance-aware temporal fusion method. We first leverages the representation (Wang et al. 2021a), i.e., a latent code in the global context (instance code) and CNN feature maps to represent instance- and pixel-level features. Based on this representation, we introduce a cropping-free temporal fusion approach to model the temporal consistency between video frames. Specifically, we encode global instance-specific information in the instance code and build up inter-frame contextual fusion with hybrid attentions between the instance codes and CNN feature maps. Inter-frame consistency between the instance codes are further enforced with order constraints. By leveraging the learned hybrid temporal consistency, we are able to directly retrieve and maintain instance identities across frames, eliminating the complicated frame-wise instance matching in prior methods. Extensive experiments have been conducted on popular VIS datasets, i.e. Youtube-VIS-19/21. Our model achieves the best performance among all online VIS methods. Notably, our model also eclipses all offline methods when using the ResNet-50 backbone.

# Summary. An optional shortened abstract.
summary: AAAI 2022

#tags:
#- Source Themes
#featured: true

links:
url_pdf: https://arxiv.org/abs/2112.01695
#url_code: https://github.com/msraig/InexactSA

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

