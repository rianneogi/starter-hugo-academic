---
title: 'On the Parameterized Complexity of Deletion to H-free Strong Components'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - M S Ramanujan
  - Saket Saurabh
  - Roohani Sharma

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2020-08-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: MFCS 2020
publication_short: MFCS 2020

abstract: 'Directed Feedback Vertex Set (DFVS) is a fundamental computational problem
that has received extensive attention in parameterized complexity. In this paper, we initiate
the study of a wide generalization, the H-free SCC Deletion problem. Here, one is given
a digraph D, an integer k and the objective is to decide whether there is a vertex set of size
at most k whose deletion leaves a digraph where every strong component excludes graphs
in the fixed finite family H as (not necessarily induced) subgraphs. When H comprises only
the digraph with a single arc, then this problem is precisely DFVS.
Our main result is a proof that this problem is fixed-parameter tractable parameterized by the size of the deletion set if H only contains rooted graphs or if H contains at
least one directed path. Along with generalizing the fixed-parameter tractability result for
DFVS, our result also generalizes the recent results of G¨oke et al. [CIAC 2019] for the
1-Out-Regular Vertex Deletion and Bounded Size Strong Component Vertex
Deletion problems. Moreover, we design algorithms for the two above mentioned problems, whose running times are better and match with the best bounds for DFVS, without
using the heavy machinery of shadow removal as is done by G¨oke et al. [CIAC 2019].'

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Parameterized Complexity]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# external_link: 'http://www.math.uwaterloo.ca/~rneogi/publication/hscc_mfcs/HSCC_MFCS.pdf'
url_pdf: 'http://www.math.uwaterloo.ca/~rneogi/publication/hscc_mfcs/HSCC_MFCS.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'http://www.math.uwaterloo.ca/~rneogi/publication/hscc_mfcs/HSCC_MFCS_slides.pdf'
url_source: ''
# url_video: 'https://www.youtube.com/watch?v=8l8HmUPVoK4'

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
