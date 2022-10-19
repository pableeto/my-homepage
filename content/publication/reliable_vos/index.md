---
title: "Reliable Propagation Correction Modulation for Video Object Segmentation"
authors:
- Xiaohao Xu*
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

abstract: Error propagation is a general but crucial problem in online semi-supervised video object segmentation. We aim to suppress error propagation through a correction mechanism with high reliability. The key insight is to disentangle the correction from the conventional mask propagation process with reliable cues. We introduce two modulators, propagation and correction modulators, to separately perform channel-wise recalibration on the target frame embeddings according to local temporal correlations and reliable references respectively. Specifically, we assemble the modulators with a cascade propagation-correction scheme. This avoids overriding the effects of the reliable correction modulator by the propagation modulator. Although the reference frame with the ground truth label provides reliable cues, it could be very different from the target frame and introduce uncertain or incomplete correlations. We augment the reference cues by supplementing reliable feature patches to a maintained pool, thus offering more comprehensive and expressive object representations to the modulators. In addition, a reliability filter is designed to predict reliable patches and pass them in subsequent frames. Our model achieves the state-of-the-art performance on YouTube-VOS18, YouTube-VOS19, DAVIS17-Test/Val benchmarks. Extensive experiments demonstrate that the correction mechanism provides considerable performance gain by fully utilizing reliable guidance.

# Summary. An optional shortened abstract.
summary: AAAI 2022

#tags:
#- Source Themes
#featured: true

links:
url_pdf: https://arxiv.org/abs/2112.02853
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

