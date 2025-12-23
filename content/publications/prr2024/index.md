---
title: "Probabilistic inference in the era of tensor networks and differential programming"

authors:
  - me
  - Xuanzhao Gao
  - Sander Stuijk
  - Henk Corporaal
  - Jin-Guo Liu

date: "2024-09-06T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-09-06T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: Journal Article

# Publication name and optional abbreviated publication name.
publication: In *Physical Review Research*
publication_short: In *Phys. Rev. Res.*

abstract: "Probabilistic inference is a fundamental task in modern machine learning. Recent advances in tensor network (TN) contraction algorithms have enabled the development of better exact inference methods. However, many common inference tasks in probabilistic graphical models (PGMs) still lack corresponding TN-based adaptations. In this paper, we advance the connection between PGMs and TNs by formulating and implementing tensor-based solutions for the following inference tasks: (A) computing the partition function, (B) computing the marginal probability of sets of variables in the model, (C) determining the most likely assignment to a set of variables, (D) the same as (C) but after having marginalized a different set of variables, and (E) generating samples from a learned probability distribution using a generalized method. Our study is motivated by recent technical advances in the fields of quantum circuit simulation, quantum many-body physics, and statistical physics. Through an experimental evaluation, we demonstrate that the integration of these quantum technologies with a series of algorithms introduced in this study significantly improves the performance efficiency of existing methods for solving probabilistic inference tasks."

# Summary. An optional shortened abstract.
summary:

tags:
  - probabilistic inference
  - graphical models
  - computational complexity

# Display this page in the Featured widget?
featured: true

hugoblox:
  ids:
    doi: "10.1103/PhysRevResearch.6.033261"

links:
  - type: pdf
    url: "https://journals.aps.org/prresearch/pdf/10.1103/PhysRevResearch.6.033261"

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
#projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
