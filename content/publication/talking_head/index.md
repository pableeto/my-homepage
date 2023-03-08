---
title: "High-Fidelity and Freely Controllable Talking Head Video Generation"
authors:
- Yue Gao 
- Yuan Zhou 
- Jinglu Wang 
- Xiao Li 
- Xiang Ming 
- Yan Lu
date: "2023-03-01T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *CVPR 2023*
publication_short: In *CVPR 2023*

abstract: Talking head generation is to generate video based on a given source identity. However, existing methods are suffering from many challenges in getting a natural and controllable video generation. First, the generated human face usually has strange deformation and severe distortions. Second, the controllability of different attributes during the generation process is limited as the movement information, including poses and expressions, is implicitly entangled in the driving image. Moreover, due to the reliability of the extracted keypoints between the adjacent frames, the generated video flickering issue also frequently exists. In this paper, we propose a novel model to produce high-fidelity talking head videos and enable head pose and expression to be freely controllable. Specifically, our method simultaneously utilizes the self-supervised learned keypoints and the 3D face model-based landmarks. A novel motion-aware multi-scale feature alignment module is proposed to effectively transfer the motion without face distortion. We further improve the smoothness of the synthesized talking head videos with a feature context adaptation and propagation module. Extensive experimental results on challenging datasets demonstrate the state-of-the-art performance of our model. The code will be made publicly available.
# Summary. An optional shortened abstract.
summary: CVPR 2023

#tags:
#- Source Themes
#featured: true

# links:
#url_pdf: https://arxiv.org/abs/2112.02853
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

