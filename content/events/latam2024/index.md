---
title: Fourth LATAM School in Software Engineering (ACM SIGSOFT-sponsored)

event: Congresso Brasileiro de Software Teoria e Prática (CBSoft 2024)
event_url: https://cbsoft.sbc.org.br/2024/cbsoft/

location: Pontifícia Universidade Católica do Paraná (PUCPR)
address:
  city: Curitiba
  region: Paraná
  country: Brasil

summary: Semantic Conflict Analysis in Continuous Software Integration with Semantic Merging Tool
abstract: 'Context/Problem: Text merge tools, which operate based on lines of code, identify conflicts when merging two versions that apply changes to the same or consecutive lines, this is not the only problem when integrating the code of two developers. Due to the limitation of considering only the combination of lines, textual merge tools cannot detect incompatible changes that occur in areas of the code separated by at least one line. Additionally, these current merge tools cannot identify dynamic semantic conflicts, which occur when a developers changes affect a state element accessed by another developers changed code, resulting in unexpected behavior during program execution. There are two main approaches to dealing with this problem: test generation and static analysis. Recently, in our research, we introduced the use of simplified static analyses, focused exclusively on the merged version of the code. However, this approach faces two significant challenges. First, these tools are restricted to identifying interferences that manifest within the same or subsequent methods, which may not adequately represent the complexity inherent in real systems. Second, their evaluation was predominantly conducted in open source environments, where direct human intervention in corporate contexts was not considered. Objectives: this study aims to propose improvements in static analyses, aiming at adapting them to operate with different entry points, in order to identify interferences in different areas of a system. Furthermore, the work presents an investigation into the use of simplified static analyzes to detect interference, with the participation of real developers in their work environments. Method: The research will be conducted in companies with developers using the tool in their daily workflows. The methodology will be divided into two phases: a quantitative one, based on the capture and analysis of logs, and a qualitative one, using forms and interviews with developers.
In the quantitative phase, the tool will be installed in the environments of participating companies for a predetermined period of time to capture detailed logs, including information on interference detection (quantity, types, precision, recall, accuracy), in addition to the execution time for each operation. of merge. After this, the data will be analyzed for the effectiveness of interference detection and tool performance. In the qualitative phase, questionnaires or interviews will be developed to collect feedback from developers on the acceptance and usability of the tool. The questionnaires will cover aspects such as ease of use, workflow integration and overall satisfaction. This way, we will have deeper insights into developers experiences and points of view. The results of the quantitative and qualitative analyzes will be combined to provide comprehensive insight into the effectiveness and performance of the semantic merge tool, as well as its acceptance and usability among developers in real development environments. The findings will be used to recommend improvements to the tool and suggest directions for future research. Expected Results: From this work, it is expected to enable the creation of an infrastructure that integrates the Git merge process to be implemented on developers machines in a corporate context, aiming to identify interferences between changes introduced by two different developers. We aim to apply our methodology in real work environments, with active developers in companies from different sectors, to integrate our tool directly into the workflows of these professionals, allowing us to capture detailed data during execution for a more accurate and comprehensive view of the use of the tool in practical scenarios. This approach will allow you to validate the effectiveness of static analysis in dynamic and complex contexts, as well as better understand developers needs and challenges. With this data, we will be able to generate informative and relevant reports, offering valuable insights for developers and research teams. Direct collaboration with professionals in the field will strengthen the validity of the approach and contribute to the advancement of knowledge and practices in detecting and resolving semantic conflicts in software projects.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-09-30T13:00:00Z'
date_end: '2024-09-30T13:00:00Z'
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: '2024-09-30T13:00:00Z'

authors:
  - admin

tags: []

# Is this a featured talk? (true/false)
featured: true

image:
  caption: 'Image credit: [**Author**]'
  focal_point: Right

links:
  - type: Event Page
    url: https://cbsoft.sbc.org.br/2024/escola/
  - type: poster
    url: https://docs.google.com/presentation/d/1nVVIwHHfEV78IC-k2zF5ckXK7_icRJAya8SL76bQlyA/edit?usp=sharing
  - type: Resume
    url: https://docs.google.com/document/d/1PzpW7sPx0TjPbkX8aAuXNFFLEoX2SE7Ck0YcHF2KIhs/edit?usp=sharing

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
