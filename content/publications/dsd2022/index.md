---
title: "Partial Evaluation in Junction Trees"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
  - me
  - Patrick Wijnings
  - Sander Stuijk 
  - Henk Corporaal

date: "2022-08-31T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-01-04T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2022 25th Euromicro Conference on Digital System Design (DSD)*
publication_short: In *DSD'22*

abstract: One prominent method to perform inference on probabilistic graphical models is the *probability propagation in trees of clusters* (PPTC) algorithm. In this paper, we demonstrate the use of *partial evaluation*, an established technique from the compiler domain, to improve the performance of online Bayesian inference using the PPTC algorithm in the context of observed evidence. We present a metaprogramming-based method to transform a base program into an optimized version by precomputing the static input at compile time while guaranteeing behavioral equivalence. We achieve an inference time reduction of 21% on average for the Promedas benchmark.

# Summary. An optional shortened abstract.
summary:


tags: 
  - junction trees
  - partial evaluation
  - Bayesian inference
  - probabilistic graphical models-
  - message passing

# Display this page in the Featured widget?
featured: false

hugoblox:
  ids:
    doi: "10.1109/DSD57027.2022.00064"

# Custom links
links:
  - type: code
    url: "https://github.com/mroavi/JunctionTrees.jl"

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
