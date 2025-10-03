---
title: "The Effect of Pointer Analysis on Semantic Conflict Detection"
authors:
  - admin
  - Paulo Borba
  - Rodrigo Bonifácio
  - Victor Lira
  - Galileu Santos
date: "2025-07-26T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-07-26T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "arxiv"
publication_short: ""

abstract: "Current merge tools don't detect semantic conflicts, which occur when changes from different developers are textually integrated but semantically interfere with each other. Although researchers have proposed static analyses for detecting semantic conflicts, these analyses suffer from significant false positive rates. To understand whether such false positives could be reduced by using pointer analysis in the implementation of semantic conflict static analyses, we conduct an empirical study. We implement the same analysis with and without pointer analysis, run them on two datasets, observe how often they differ, and compare their accuracy and computational performance. Although pointer analysis is known to improve precision in static analysis, we find that its effect on semantic conflict detection can be drastic: we observe a significant reduction in timeouts and false positives, but also a significant increase in false negatives, with prohibitive drops in recall and F1-score. These results suggest that, in the context of semantic conflict detection, we should explore hybrid analysis techniques, combining aspects of both implementations we compare in our study."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - merge tools,
  - semantic conflict
  - static analysis
  - pointer analysis

featured: true

hugoblox:
  ids:
    doi: 10.48550/arXiv.2507.20081

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
    url: https://anonymous.4open.science/w/papers-AEC8/the-effect-of-pointer-analysis-for-semantic-conflict-detection.html

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
  - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

Subjects: Software Engineering (cs.SE)
