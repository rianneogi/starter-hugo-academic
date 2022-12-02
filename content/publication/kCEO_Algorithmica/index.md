---
title: 'Recognizing k-Clique Extendible Orderings'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Mathew Francis
  - admin
  - Venkatesh Raman

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2021-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1','2']

# Publication name and optional abbreviated publication name.
publication: Algorithmica 2021
publication_short: Algorithmica 2021
publication_extra: Preliminary version appeared in <b>WG 2020</b>

abstract: We consider the complexity of recognizing k-clique-extendible graphs (k-C-E graphs) introduced by Spinrad (Efficient Graph Representations, AMS 2003), which are generalizations of comparability graphs. A graph is k-clique-extendible if there is an ordering of the vertices such that whenever two overlapping k-cliques A and B have k−1 common vertices, and these common vertices appear between the two vertices a,b∈(A∖B)∪(B∖A) in the ordering, there is an edge between a and b, implying that A∪B is a (k+1)-clique. Such an ordering is said to be a k-C-E ordering. These graphs arise in applications related to modelling preference relations. Recently, it has been shown that a maximum clique in such a graph can be found in nO(k) time [Hamburger et al. 2017] when the ordering is given. When k is 2, such graphs are precisely the well-known class of comparability graphs and when k is 3 they are called triangle-extendible graphs. It has been shown that triangle-extendible graphs appear as induced subgraphs of visibility graphs of simple polygons, and the complexity of recognizing them has been mentioned as an open problem in the literature. While comparability graphs (i.e. 2-C-E graphs) can be recognized in polynomial time, we show that recognizing k-C-E graphs is NP-hard for any fixed k≥3 and CO-NP-hard when k is part of the input. While our NP-hardness reduction for k≥4 is from the betweenness problem, for k=3, our reduction is an intricate one from the 3-colouring problem. We also show that the problems of determining whether a given ordering of the vertices of a graph is a k-C-E ordering, and that of finding a maximum clique in a k-C-E graph, given a k-C-E ordering, are hard for the parameterized complexity classes CO-W[1] and W[1] respectively, when parameterized by k. However we show that the former is fixed-parameter tractable when parameterized by the treewidth of the graph. We also show that the dual parameterizations of all the problems that we study are fixed parameter tractable.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Parameterized Complexity]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: arXiv
  url: https://arxiv.org/abs/2007.06060

# external_link: 'http://www.math.uwaterloo.ca/~rneogi/publication/kceo_algorithmica/kCEO_Algorithmica.pdf'
url_pdf: 'http://www.math.uwaterloo.ca/~rneogi/publication/kceo_algorithmica/kCEO_Algorithmica.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'http://www.math.uwaterloo.ca/~rneogi/publication/kceo_algorithmica/kCEO_wg2020_slides.pdf'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
