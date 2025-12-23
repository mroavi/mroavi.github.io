---
title: "Pushing the Boundaries of Probabilistic Inference through Message Contraction Optimization"
authors:
- me
- Jin-Guo Liu
- Patrick Wijnings
- Sander Stuijk 
- Henk Corporaal
date: "2024-07-24T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-07-24T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["6"]

# Publication name and optional abbreviated publication name.
publication: In the *Artificial Intelligence - Machine Learning, Convolutional Neural Networks and Large Language Models*
publication_short: In *Artificial Intelligence*

abstract: A key aspect of intelligent systems is their capacity to reason under uncertainty. This task involves calculating probabilities of relevant variables while considering any available information, a process commonly referred to as probabilistic inference. When working with discrete variables, the primary operations in probabilistic inference algorithms involve adding and multiplying multidimensional arrays with labeled dimensions, known as factors. The algorithmic complexity is dictated by the highest dimensional factor involved in any calculation; a concept referred to as the induced tree width. Despite advances in state-of-the-art techniques focused on reducing this metric, many real-world problems remain too complex to solve through existing probabilistic inference algorithms. In this work, we introduce a new method for adding and multiplying factors, which leads to marked improvements in inference performance, particularly for more complex models. Furthermore, this method serves as the core of a novel optimization framework introduced in this work, which employs metaprogramming to further enhance the runtime performance of probabilistic inference algorithms. Our method complements current leading-edge techniques aimed at reducing the induced tree width, thereby extending the range of models that can be effectively solved using exact inference. To validate the performance of our approach, we compare it against two other open-source libraries designed for probabilistic inference. Our method demonstrates an average speedup of 23 times on the UAI 2014 benchmark set. For the 10 most complex problems of this set, the average speedup increases to 64 times, highlighting the scalability of our method.

# Summary. An optional shortened abstract.
summary:

tags: [probabilistic inference, message-passing algorithms, probabilistic graphical models, Bayesian networks]

# Display this page in the Featured widget?
featured: false

hugoblox:
  ids:
    doi: "10.1515/9783111344126-002"

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
