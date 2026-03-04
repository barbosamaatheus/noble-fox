---
title: "Comparing static analyses for improved semantic conflict detection"
authors:
  - Galileu Santos
  - Paulo Borba
  - Rodrigo Bonifácio
  - admin
date: "2025-12-23T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-12-23T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "Automated Software Engineering, Volume 33, Issue 2"
publication_short: "ASE2025"

abstract: "Version control systems are essential in software development, allowing teams to collaborate simultaneously without interfering with each other’s work. Tools like Git facilitate code integration through merge operations, which automatically detect textual conflicts. However, these systems focus solely on source code differences, overlooking more complex semantic conflicts that can lead to failures or unexpected behavior after integration. To address this challenge, static analysis emerges as an effective solution, detecting semantic conflicts that traditional merge tools might miss, providing an additional layer of security and quality to the code integration process. In this study, we explore combinations of static analysis techniques to improve the detection of semantic conflicts. Our approach was evaluated on a dataset from 32 real-world GitHub projects, all manually labeled to include ground truth information. These outcomes highlight the adaptability of our approach: in contexts where minimizing false positives is essential, high-precision techniques can be prioritized; in contrast, recall-focused techniques are preferable for broader conflict coverage. The results show that combining static analysis strategies delivers superior performance in terms of precision, recall, F1 score, and accuracy compared to previous methods, and is a more lightweight and flexible approach to adapt to the application context."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - merge tools,
  - semantic conflict
  - static analysis

featured: false

hugoblox:
  ids:
    doi: 10.1007/s10515-025-00580-y

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
  #- type: custom
  #  label: Online Appendix
  #  url: https://anonymous.4open.science/w/papers-AEC8/the-effect-of-pointer-analysis-for-semantic-conflict-detection.html

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: "Image credit: [**Gemini**](https://gemini.google.com/)"
#  focal_point: ""
#  preview_only: false

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
