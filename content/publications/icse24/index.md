---
title: "Lightweight Semantic Conflict Detection with Static Analysis"
authors:
  - Galileu Santos De Jesus
  - Paulo Borba
  - Rodrigo Bonifácio,
  - admin
date: "2024-05-23T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-05-23T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "ICSE-Companion '24: Proceedings of the 2024 IEEE/ACM 46th International Conference on Software Engineering: Companion Proceedings"
publication_short: "ICSE-Companion '24: Proceedings of the 2024 IEEE/ACM 46th International Conference on Software Engineering: Companion Proceedings"

abstract: Version control system tools empower developers to independently work on their development tasks. These tools also facilitate the integration of changes through merging operations, and report textual conflicts. However, during the integration of changes, developers might encounter other types of conflicts that are not detected by current merge tools. In this paper, we focus on dynamic semantic conflicts, which occur when merging reports no textual conflicts but results in undesired interference---causing unexpected program behavior at runtime. To address this issue, we propose a technique that explores the use of static analysis to detect interference when merging contributions from two developers. We evaluate our technique using a dataset of 99 experimental units extracted from merge scenarios. The results provide evidence that our technique presents significant interference detection capability (F1 Score of 0.50 and Accuracy of 0.60).

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Merge conflicts
  - Configuration management
  - Software evolution
  - Static analysis

featured: false

hugoblox:
  ids:
    doi: 10.1145/3639478.3643118

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
slides: ""
---
