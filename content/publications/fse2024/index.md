---
title: "Semantic Conflict Analysis in Continuous Software Integration with Semantic Merging Tool"
authors:
  - admin
date: "2024-07-15T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-07-15T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "FSE 2024 Doctoral Symposium"
publication_short: "FSE 2024 Doctoral Symposium"

abstract: The functionalities of the version control system enable developers to carry out their development tasks autonomously. Additionally, these tools simplify incorporating changes through merge operations and identify text conflicts. Textual conflicts are significant adversities, however, there are other forms of conflicts that can be even more harmful and are not identified by currently available merge tools. Dynamic semantic conflicts refer to situations in which there are no apparent textual conflicts during the merge reports, however, they result in unwanted interference that can cause unexpected behavior of the program during its execution. There are currently a variety of tools available that take different approaches to addressing this challenge. These range from static analyzes to the implementation of automated tests. However, it is observed that the test-centric approach generally results in a higher number of false negatives, while static analyzes tend to have a higher incidence of false positives. Additionally, these tools are limited to identifying interferences that occur within the same method or in subsequent methods, which may not reflect the real complexity of the systems. Furthermore, they were evaluated mainly in open source scenarios, without the direct insertion of human intervention in corporate environments. In this study, we propose improving static analyzes to enable their execution with different entry points, aiming to identify interferences in different areas of a system. Furthermore, we propose the use of a semantic merge tool that integrates the Git merge process, to be implemented on developers’ machines in an industrial-strength context. This will enable the collection of merge reports, allowing an analysis of performance and accuracy using the active participation of the professionals involved as ground truth.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - code integration conflicts
  - dynamic semantic conflicts
  - semantic merge tool

featured: false

links:
  - type: preprint
    url: https://2024.esec-fse.org/details/fse-2024-doctoral-symposium/7/Semantic-Conflict-Analysis-in-Continuous-Software-Integration-with-Semantic-Merging-T
  - type: slides
    url: https://2024.esec-fse.org/details/fse-2024-doctoral-symposium/7/Semantic-Conflict-Analysis-in-Continuous-Software-Integration-with-Semantic-Merging-T

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
