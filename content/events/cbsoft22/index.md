---
title: XXXVI Simpósio Brasileiro de Engenharia de Software (SBES)

event: Congresso Brasileiro de Software Teoria e Prática (CBSoft 2022)
event_url: https://cbsoft2022.facom.ufu.br/

location: ON-LINE
address:
  city: Uberlândia
  region: Minas Gerais
  country: Brasil

summary: Detection of semantic conflicts with static overriding assignment analysis
abstract: Developers typically work collaboratively and often need to embed their code into a major version of the system. This process can cause merge conflicts, affecting team productivity. Some of these conflicts require understanding software behavior (semantic conflicts) and current version control tools are not able to detect that. So here we explore how such conflicts could be automatically detected using static analysis of the integrated code. We propose and implement an assignment overriding analysis, which aims to detect interference between changes introduced by two different developers, where write paths, without intermediate assignments, to a common target indicate interference. To evaluate the implementations of the proposed analysis, a set of 78 code integration scenarios was used. The results show that the proposed analysis is able to detect scenarios with assignment overriding and with locally observable interference between the contributions.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2022-10-03T13:00:00Z"
date_end: "2022-10-10T13:00:00Z"
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: "2022-10-10T13:00:00Z"

authors:
  - admin
  - Paulo Borba
  - Rodrigo Bonifácio
  - Galileu Santos

tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: "Image credit: [**Author**]"
  focal_point: Right

links:
  - type: Event Page
    url: https://cbsoft2022.facom.ufu.br/
  - type: link
    url: https://dl.acm.org/doi/10.1145/3555228.3555242
  - type: slides
    url: https://docs.google.com/presentation/d/1HC3Y1TB0-9J8pdkeEuW70H4Sr9mUyxngW2y__KM5qwQ/edit?usp=sharing

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
