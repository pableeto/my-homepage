---
title: "Estimating Neural Reflectance Field from Radiance Field using Tree Structures"
authors:
- Xiu Li*
- Xiao Li
- Yan Lu
date: "2022-07-09T00:00:00Z"
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

abstract: We present a new method for estimating the Neural \textbf{Reflectance} Field (NReF) of an object from a set of posed multi-view images under unknown lighting. NReF represents 3D geometry and appearance of objects in a disentangled manner, and are hard to be estimated from images only. Our method solve this problem by exploiting the Neural \textbf{Radiance} Field (NeRF) as a proxy representation, from which we perform further decomposition. A high-quality NeRF decomposition relies on good geometry information extraction as well as good prior terms to properly resolve ambiguities between different components. To extract high-quality geometry information from radiance fields, we re-design a new ray-casting based method for surface point extraction. To efficiently compute and apply prior terms, we convert different prior terms into different type of filter operations on the surface extracted from radiance field. We then employ two type of auxiliary data structures, namely Gaussian KD-tree and octree, to support fast querying of surface points and efficient computation of surface filters during training. Based on this, we design a multi-stage decomposition optimization pipeline for estimating neural reflectance field from neural radiance fields. Extensive experiments show our method outperforms other state-of-the-art methods on different data, and enable high-quality free-view relighting as well as material editing tasks.

# Summary. An optional shortened abstract.
summary: arxiv Preprint

#tags:
#- Source Themes
#featured: true

links:
url_pdf: https://arxiv.org/pdf/2210.04217
# url_code: https://github.com/msraig/InexactSA

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

