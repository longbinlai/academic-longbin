---
title: "Distributed Subgraph Matching on Timely Dataflow"
authors:
- admin
- Zhu Qin
- Zhengyi Yang
- Xin Jin
- Zhengmin Lai
- Ran Wang
- Kongzhang Hao
- Xuemin Lin
- Lu Qin
- Wenjie Zhang
- Ying Zhang
- Zhengping Qian
- Jingren Zhou
date: "2019-07-01T00:00:00Z"
doi: "10.14778/3339490.3339494"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Proceedings of the VLDB Endowment
publication_short: In *VLDB*

abstract: Recently there emerge many distributed algorithms that aim at solving subgraph matching at scale. Existing algorithm-level comparisons failed to provide a systematic view of distributed subgraph matching mainly due to the intertwining of strategy and optimization. In this paper, we identify four strategies and three general-purpose optimizations from representative state-of-the-art algorithms. We implement the four strategies with the optimizations based on the common Timely dataflow system for systematic strategy-level comparison. Our implementation covers all representative algorithms. We conduct extensive experiments for both unlabelled matching and labelled matching to analyze the performance of distributed subgraph matching under various settings, which is finally summarized as a practical guide.

# Summary. An optional shortened abstract.
summary: 

tags:
- Source Themes
featured: false

links:
- name: Custom Link
  url: http://lai.me
url_pdf: static/p1099-lai.pdf
url_code: '#'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: https://docs.google.com/presentation/d/137NVBRu6kl_wLv53ys-FKAvIr-dM7al_L5gJ8DU1HIs/edit?usp=sharing
url_source: '#'
url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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
slides: example
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).

