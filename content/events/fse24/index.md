---
title: FSE 2024 Doctoral Symposium

event: ACM International Conference on the Foundations of Software Engineering (FSE)
event_url: https://2024.esec-fse.org/track/fse-2024-doctoral-symposium

location: Armação Resort
address:
  city: Porto de Galinhas
  region: Pernambuco
  country: Brasil

summary: Semantic Conflict Analysis in Continuous Software Integration with Semantic Merging Tool
abstract: The functionalities of the version control system enable developers to carry out their development tasks autonomously. Additionally, these tools simplify incorporating changes through merge operations and identify text conflicts. Textual conflicts are significant adversities, however, there are other forms of conflicts that can be even more harmful and are not identified by currently available merge tools. Dynamic semantic conflicts refer to situations in which there are no apparent textual conflicts during the merge reports, however, they result in unwanted interference that can cause unexpected behavior of the program during its execution. There are currently a variety of tools available that take different approaches to addressing this challenge. These range from static analyzes to the implementation of automated tests. However, it is observed that the test-centric approach generally results in a higher number of false negatives, while static analyzes tend to have a higher incidence of false positives. Additionally, these tools are limited to identifying interferences that occur within the same method or in subsequent methods, which may not reflect the real complexity of the systems. Furthermore, they were evaluated mainly in open source scenarios, without the direct insertion of human intervention in corporate environments. In this study, we propose improving static analyzes to enable their execution with different entry points, aiming to identify interferences in different areas of a system. Furthermore, we propose the use of a semantic merge tool that integrates the Git merge process, to be implemented on developers’ machines in an industrial-strength context. This will enable the collection of merge reports, allowing an analysis of performance and accuracy using the active participation of the professionals involved as ground truth.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2024-06-15T13:00:00Z"
date_end: "2024-06-15T13:00:00Z"
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: "2024-06-15T13:00:00Z"

authors:
  - admin

tags: []

# Is this a featured talk? (true/false)
featured: true

image:
  caption: "Image credit: [**Author**]"
  focal_point: Right

links:
  - type: Event Page
    url: https://2024.esec-fse.org/track/fse-2024-doctoral-symposium
  - type: poster
    url: https://docs.google.com/presentation/d/1IPCbq8AyG2H-5y_6K9mxfqu3n48EeR9d0kKWGxmzsr0/edit?usp=sharing
  - type: preprint
    url: https://2024.esec-fse.org/details/fse-2024-doctoral-symposium/7/Semantic-Conflict-Analysis-in-Continuous-Software-Integration-with-Semantic-Merging-T
  - type: slides
    url: https://2024.esec-fse.org/details/fse-2024-doctoral-symposium/7/Semantic-Conflict-Analysis-in-Continuous-Software-Integration-with-Semantic-Merging-T

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - semantic-merge-tool
---
