---
title: "Semantic conflict detection with overriding assignment analysis"
authors:
  - admin
  - Paulo Borba
  - Rodrigo Bonifácio
  - Galileu Santos
date: "2022-10-05T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-10-05T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Developers typically work collaboratively and often need to embed their code into a major version of the system. This process can cause merge conflicts, affecting team productivity. Some of these conflicts require understanding software behavior (semantic conflicts) and current version control tools are not able to detect that. So here we explore how such conflicts could be automatically detected using static analysis of the integrated code. We propose and implement an assignment overriding analysis, which aims to detect interference between changes introduced by two different developers, where write paths, without intermediate assignments, to a common target indicate interference. To evaluate the implementations of the proposed analysis, a set of 78 code integration scenarios was used. The results show that the proposed analysis is able to detect scenarios with assignment overriding and with locally observable interference between the contributions.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - code integration conflicts

featured: true

hugoblox:
  ids:
    doi: 10.1145/3555228.3555242

links:
  #  - type: preprint
  #    provider: arxiv
  #    id: 1512.04133v1
  #  - type: code
  #    url: https://github.com/HugoBlox/hugo-blox-builder
  #  - type: slides
  #    url: https://www.slideshare.net/
  # - type: dataset
  #    url: "#"
  #  - type: poster
  #    url: "#"
  #  - type: source
  #    url: "#"
  #  - type: video
  #    url: https://youtube.com
  - type: custom
    label: Online Appendix
    url: https://spgroup.github.io/papers/semantic-conflicts-SBES2022.html

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: "Image credit: [**Gemini**](https://gemini.google.com/)"
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - semantic-merge-tool
# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: ""
---

SBES '22: Proceedings of the XXXVI Brazilian Symposium on Software Engineering
