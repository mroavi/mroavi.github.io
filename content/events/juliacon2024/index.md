---
title: Probabilistic inference using contraction of tensor networks

event: JuliaCon 2024
event_url: https://juliacon.org/2024/

#location: Hugo Blox Builder HQ
#address:
#  street: 450 Serra Mall
#  city: Stanford
#  region: CA
#  postcode: '94305'
#  country: United States

summary: TensorInference, a package for exact probabilistic inference in discrete graphical models, capitalizes on recent tensor network advancements. Its tensor-based engine features optimized contraction ordering methods, an aspect vital to computational performance. Additionally, it incorporates optimized BLAS routines and GPU technology for enhanced efficiency. In a comparative evaluation with similar libraries, TensorInference demonstrates superior scalability for models of increasing complexity.

abstract: "Reasoning under uncertainty is a key challenge in fields like AI,
medical diagnosis, computer vision, and natural language processing.
Probabilistic graphical models (PGMs) are crucial for this, representing
complex systems' joint probability distributions efficiently.

Despite PGMs' utility, probabilistic inference remains a complex task due to
the high-dimensional combinatorial optimization involved. To address this, we
introduce TensorInference.jl, a Julia package that combines PGMs with tensor
network computational power to improve probabilistic inference performance for
complex models.

Probabilistic inference calculates probabilities from observed data using
probability theory axioms. Inference methods are categorized into exact and
approximate. Exact methods face NP-hard computational challenges related to
the model's treewidth. In contrast, approximate methods like Markov chain
Monte Carlo and variational inference, implemented in packages like Stan and
PyMC3, offer scalability but lack formal accuracy guarantees. Thus, exact
methods are resurging for their accuracy potential.

TensorInference.jl utilizes recent tensor network advances to provide exact
high-performance solutions for inference problems. It enables tasks like
calculating partition functions, computing marginal probabilities, finding
likely variable assignments, and drawing posterior samples.

Tensor networks, like PGMs, are adept at representing complex system states.
Computational efficiency in tensor networks hinges on the contraction
sequence; hence, optimizing this order is vital.

TensorInference.jl enhances computational tasks using differentiable
programming, supports generic element types, and allows for hyper-optimized
contraction order settings. It includes advanced contraction methods including
a local search-based method, denoted as TreeSA, two methods based on min-cut
algorithms, denoted as SABipartite and KaHyParBipartite, as well as a greedy
algorithm, denoted as GreedyMethod. Additionally, it incorporates BLAS
routines and GPU technology for improved performance.
"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-07-10T14:00:00Z'
date_end: '2024-07-10T14:40:30Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2024-07-10T14:00:00Z'

authors:
  - me

tags: 
  - JuliaCon

featured: true

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
 - url: 'https://github.com/TensorBFS/TensorInference.jl'
#url_pdf: ''
#url_slides: 'https://github.com/mroavi/juliacon2024/blob/main/out/main.pdf'
#url_video: 'https://www.youtube.com/live/1c4TTosBzzY?si=WXoCZl6FUmYg2KSN&t=16863'

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects:
#  - example
---
