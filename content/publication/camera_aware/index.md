---
title: "Mimicking the In-Camera Color Pipeline for Camera-Aware Object Compositing"
authors:
"Jun Gao, Xiao Li, Liwei Wang, Sanja Fidler, Stephen Lin"
- Jun Gao
- Xiao Li
- Liwei Wang
- Sanja Fidler
- Stephen Lin
date: "2019-03-27T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *arxiv*
publication_short: In *arxiv*

abstract: We present a method for compositing virtual objects into a photograph such that the object colors appear to have
been processed by the photo’s camera imaging pipeline. Compositing in such a camera-aware manner is essential
for high realism, and it requires the color transformation in the photo’s pipeline to be inferred, which is challenging
due to the inherent one-to-many mapping that exists from a scene to a photo. To address this problem for the case of
a single photo taken from an unknown camera, we propose a dual-learning approach in which the reverse color transformation (from the photo to the scene) is jointly estimated.
Learning of the reverse transformation is used to facilitate learning of the forward mapping, by enforcing cycle consistency of the two processes. We additionally employ a feature sharing schema to extract evidence from the target photo in the reverse mapping to guide the forward color transformation. Our dual-learning approach achieves object compositing results that surpass those of alternative techniques.

# Summary. An optional shortened abstract.
summary: arxiv Preprint

#tags:
#- Source Themes
#featured: true

links:
url_pdf: https://arxiv.org/abs/1903.11248

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

