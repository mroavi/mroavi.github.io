---
title: "On the Importance of the Execution Schedule for Bayesian Inference"

authors:
  - Patrick Wijnings
  - me
  - Sander Stuijk 
  - Bert de Vries
  - Henk Corporaal

date: "2024-08-31T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-08-31T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *ACM Transactions on Probabilistic Machine Learning*
publication_short: In *ACM TOPML*

abstract: Bayesian inference is a probabilistic approach to the problem of drawing conclusions from observed data. Its main challenge is computational, which the Bayesian community tends to address through approximation techniques. However, these techniques come with their own set of challenges, including approximation errors, the difficulty of assessing these errors, and the inherited NP-hardness of the inference problem. Concurrently, in an effort to keep up with Moore’s law, the computer engineering community has developed an increasing number of programming techniques for today’s heterogeneous hardware. These techniques aim to optimize the execution schedule, which refers to the order and mapping of computations on the available execution units. In this work, we advocate for the utilization of these techniques to avoid a common pitfall known as premature approximation. Notably, these techniques have the potential to significantly enhance performance, thereby reducing the need for approximation and thus mitigating the challenges that accompany it. We first demonstrate how optimization of the storage strategy, i.e. when and where intermediate results are stored, allows for a trade-off between runtime and peak memory usage. We then investigate various techniques that aim to automatically generate efficient execution schedules. Finally, we focus on a specific, runtime-efficient execution schedule identified through design space exploration and compare its performance with that of two established solvers for probabilistic inference. The results show that our optimized implementation achieves speedups ranging from to for the UAI 2014 Promedus benchmark problems compared to the reference solvers. The ideas and methods presented in our study are examined within the framework of exact inference for discrete random variables. However, they are effectively applicable to scenarios involving continuous variables.

# Summary. An optional shortened abstract.
summary:

tags:
  - Bayesian inference
  - probabilistic graphical models
  - computational performance

# Display this page in the Featured widget?
featured: true

links:
  - type: source
    url: "https://dl.acm.org/doi/10.1145/3690830"

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
