---
title: "Characterizing X86 and ARM Serverless Performance Variation: A Natural Language Processing Case Study"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Danielle Lambion
- Robert Cordingly
- Navid Heydari
- Wes Lloyd

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: ""
doi: "10.1145/3491204.3543506"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-05-16T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Companion of the 2022 ACM/SPEC International Conference on Performance Engineering
publication_short: ICPE '22 Companion

abstract: In this paper, we leverage a Natural Language Processing (NLP) pipeline for topic modeling consisting of three functions for data preprocessing, model training, and inferencing to analyze serverless platform performance variation. Specifically, we investigated performance using x86_64 and ARM64 processors over a 24-hour day starting at midnight local time on four cloud regions across three continents on AWS Lambda. We identified public cloud resource contention by leveraging the CPU steal metric, and examined relationships to NLP pipeline runtime. Intel x86_64 Xeon processors at the same clock rate as ARM64 processors (Graviton 2) were more than 23% faster for model training, but ARM64 processors were faster for data preprocessing and inferencing. Use of the Intel x86_64 architecture for the NLP pipeline was up to 33.4% more expensive than ARM64 as a result of incentivized pricing from the cloud provider and slower pipeline runtime due to greater resource contention for Intel processors.

# Summary. An optional shortened abstract.
summary: 

tags: [Function-as-a-Service, Topic Modeling, Performance Variation, Resource Contention, Serverless Computing]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: publication/conference-paper/hotcloudperf_lambda_variability.pdf
url_code: https://github.com/lambiond/faas_variability_topic_modeling
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://raw.githubusercontent.com/lambiond/faas_variability_topic_modeling/main/hotcloudperf-presentation.pdf'
url_source: ''
url_video: 'https://youtu.be/VEF3i_XNGy0?t=11354'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:  ""
---
