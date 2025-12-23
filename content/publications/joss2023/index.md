---
title: "TensorInference: A Julia package for tensor-based probabilistic inference"

authors:
  - me
  - Jin-Guo Liu
date: "2023-10-03T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-10-03T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: Journal Article

# Publication name and optional abbreviated publication name.
publication: In *The Jouornal of Open Source Software*
publication_short: In *JOSS*

#abstract: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. Sed ac faucibus dolor, scelerisque sollicitudin nisi. Cras purus urna, suscipit quis sapien eu, pulvinar tempor diam. Quisque risus orci, mollis id ante sit amet, gravida egestas nisl. Sed ac tempus magna. Proin in dui enim. Donec condimentum, sem id dapibus fringilla, tellus enim condimentum arcu, nec volutpat est felis vel metus. Vestibulum sit amet erat at nulla eleifend gravida.

# Summary. An optional shortened abstract.
summary: Probabilistic inference is a central task in intelligent systems, enabling reasoning under uncertainty across domains such as artificial intelligence, medical diagnosis, and computational biology. Although probabilistic graphical models provide a compact representation of complex joint distributions, exact inference remains computationally intractable for many real-world models due to its dependence on high-dimensional combinatorial optimization. As a result, approximate methods dominate practice, despite their lack of formal accuracy guarantees. TensorInference.jl is a Julia package for exact probabilistic inference in discrete graphical models that combines the representational strengths of graphical models with the computational efficiency of tensor networks. By formulating inference tasks as tensor network contractions and leveraging state-of-the-art contraction ordering algorithms, differentiable programming, and optimized linear algebra backends, TensorInference.jl delivers high-performance solutions for key inference problems, including partition function computation, marginalization, MAP and MMAP inference, and posterior sampling. This holistic tensor network approach expands the tractability of exact inference for more complex models and provides a flexible, extensible framework for research and application in probabilistic reasoning.

tags:
  - probabilistic graphical models
  - tensor networks
  - probabilistic inference

# Display this page in the Featured widget?
featured: true

hugoblox:
  ids:
    doi: "10.21105/joss.05700"

links:
  - type: pdf
    url: "https://doi.org/10.21105/joss.05700"
  - type: code
    url: "https://github.com/TensorBFS/TensorInference.jl"

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
