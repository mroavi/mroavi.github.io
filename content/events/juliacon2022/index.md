---
title: JunctionTrees.jl - Efficient Bayesian Inference in Discrete Graphical Models

event: JuliaCon 2022
event_url: https://juliacon.org/2022/

#location: Hugo Blox Builder HQ
#address:
#  street: 450 Serra Mall
#  city: Stanford
#  region: CA
#  postcode: '94305'
#  country: United States

summary: JunctionTrees.jl implements the junction tree algorithm, an efficient method to perform Bayesian inference in discrete probabilistic graphical models. It exploits Julia's metaprogramming capabilities to separate the algorithm into a compilation and a runtime phase. This opens a wide range of optimization possibilities in the compilation stage. The non-optimized runtime performance of JunctionTrees.jl is similar to those of analog C++ libraries such as libdai and Merlin.
abstract: | 
  'JunctionTrees.jl encapsulates the result of the research we have been conducting in the context of improving the efficiency of Bayesian inference in probabilistic graphical models. The junction tree algorithm is a core component of discrete inference in probabilistic graphical models. It lies at the heart of many courses that are taught at different universities around the world including MIT, Berkeley, and Stanford. Moreover, it serves as the backbone of successful commercial software, such as Hugin Expert, that aims to discover insight and provide predictive capabilities to effectively combat fraud and risk. JunctionTrees.jl is mainly tailored towards students and researchers. This library offers a great starting point for understanding the implementation details of this algorithm thanks to the intrinsic readability of the Julia language and the thoroughly commented codebase. Moreover, this package constitutes an optimization framework that other researchers can make use of to experiment with different ideas to improve the performance of runtime Bayesian inference.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2022-07-27T14:30:00Z'
date_end: '2022-07-27T14:40:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2022-07-27T14:30:00Z'

authors:
  - me

tags: 
  - JuliaCon
  - junction tree algorithm
  - probabilistic inference
  - message-passing algorithms

featured: true

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

links:
  - name: Video
    url: https://youtu.be/5oPLzMh7ckQ?si=hGFr973DOUnnF8W3
  #- name: Source code
  #  url: https://github.com/mroavi/JunctionTrees.jl

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
