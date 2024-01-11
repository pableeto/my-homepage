---
title: "Unsupervised Temporal Correspondence Learning for Unified Video Object Removal"
authors:
- Zhongdao Wang*
- Jinglu Wang
- Xiao Li
- Ya-Li Li
- Yan Lu
- Shengjin Wang
date: "2023-12-20T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Image Processing
publication_short: TIP

abstract: Video object removal aims at erasing a target object in the entire video and filling holes with plausible contents, given an object mask in the first frame as input. Existing solutions mostly break down the task into (supervised) mask tracking and (self-supervised) video completion, and then separately tackle them with tailored designs. In this paper, we introduce a new setup, coined as unified video object removal, where mask tracking and completion are addressed within a unified framework. Despite introducing more challenges, the setup is promising for future practical usage. We embrace the observation that these two sub-tasks have strong inherent connections in terms of pixel-level temporal correspondence. Making full use of the connections could be beneficial considering the complexity of both algorithm and deployment. We propose a single network linking the two sub-tasks by inferring temporal correspondences across multiple frames, i.e. , correspondences between valid-valid (V-V) pixel pairs for mask tracking and correspondences between valid-hole (V-H) pixel pairs for video completion. Thanks to the unified setup, the network can be learned end-to-end in a totally unsupervised fashion without any annotations. We demonstrate that our method can generate visually pleasing results and perform favorably against existing separate solutions in realistic test cases.

# Summary. An optional shortened abstract.
summary: IEEE Transactions on Image Processing

#tags:
#- Source Themes
#featured: true

links:
url_pdf: https://ieeexplore.ieee.org/document/10359477
# url_code: https://github.com/JerryX1110/RPCMVOS

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

