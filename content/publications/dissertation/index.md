---
title: "Detecção de conflitos semânticos via análise estática de substituição de atribuição"
authors:
  - admin
date: "2022-02-23T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-02-23T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["dissertation"]

# Publication name and optional abbreviated publication name.
publication: "in *Repositorio Digital UFPE"
publication_short: "UFPE"

abstract: "The current software development process, except in special cases, is done collaboratively. As new requirements are raised, new tasks are defined and allocated to different developers. Developers, as far as they are concerned, add their modifications to separate and isolated repositories or versions of the code, and later these modifications need to be integrated into a central repository or version. This code integration process is error prone, especially if changes in different branches conflict. Some of these conflicts are simpler and can be detected by current version control tools like Git, however they still require human intervention to resolve them, which affects team productivity. But that’s not the only problem, there are also semantic conflicts that require understanding the behavior of software, which is beyond the capabilities of most existing merge tools. These conflicts are hardly noticed by reviews or detected in tests, reaching the end-user as a software defect. This type of conflict occurs when, in the integrated code, changes introduced by one developer’s version unexpectedly interfere with changes introduced by another developer’s version, causing a contract intended by one of the versions to be unfulfilled. Therefore, tools are needed that can detect conflicts of this type in the integration process, in order to avoid bugs and facilitate their resolution. In this sense, this work proposes an analysis of assignment substitution (Override an Assignment (OA)), which aims to detect interference between changes introduced by two different developers, where recording paths, without intermediate assignments, to a target common indicate interference. The implementation and evaluation of two approaches (interprocedural and intraprocedural) for the proposed analysis was also carried out. To evaluate the implementations of the proposed analysis, a set of 78 code integration scenarios was used, in which both integrated versions modified the same method. These scenarios were extracted from open-source Java projects, mined by Github’s integration scenario mining tool. The results show that the proposed analysis was able to detect scenarios with assignment substitutions and with locally observable interference between the contributions, however, it had a considerable amount of false negatives, which indicates that it is not sufficient to detect scenarios with interference. reliably. However, the proposed analysis could be combined with other analyzes to compose a more robust tool for detecting semantic integration conflicts."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - override assignment
  - code integration conflicts
  - collaborative development

featured: false

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
  - type: link
    url: "https://repositorio.ufpe.br/handle/123456789/44697"
  #  - type: video
  #    url: https://youtube.com
  #- type: custom
  #  label: Online Appendix
  #  url: https://anonymous.4open.science/w/papers-AEC8/the-effect-of-pointer-analysis-for-semantic-conflict-detection.html

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - plugged-computing

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
