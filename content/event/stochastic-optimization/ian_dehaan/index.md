---
title: Greedy algorithm for stochastic matching is a 2-approximation
draft: false

# event: Stochastic Optimization
# event_url: '/event/combopt-group/stochastic-optimization'
subtitle: Ian DeHaan
topic: Stochastic Optimization
topic_url: 'https://www.math.uwaterloo.ca/~rneogi/comb-opt-group/event/stochastic-optimization/'
share: false
show_abstract_button: true

location: MC6029 or Zoom
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

# summary: An example talk using Wowchemy's Markdown slides feature.
abstract: 'We will discuss the greedy algorithm for the stochastic matching problem. In this problem, we are given an undirected graph where each edge is assigned a probability p_e in [0, 1] and each vertex is assigned a patience t_v in Z+. We begin each step by probing an edge e which is not adjacent to any edges in our matching. The probe will succeed with probability p_e, and if it does, we add e to our matching. Otherwise, we may not probe e again. We also may not probe edges adjacent to a vertex v more than t_v times. The goal is to maximize the number of edges we add to our matching.
A greedy approach was shown to be a 4-approximation for stochastic matching in a previous talk by David Kalichman through analysis of a more general problem. In this talk, we will show that greedy is a 2-approximation for the special case of stochastic matching.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2022-11-25T12:00:00Z'
# date_end: '2030-06-01T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors: ['']
# tags: ['Stochastic Optimization']

# Is this a featured talk? (true/false)
featured: false

# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#   focal_point: Right

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
# url_slides: 'Slides/fukasawa.pdf'
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects:
#   - example
---

<!-- **Topic:**   [Stochastic Optimization]('http://www.math.uwaterloo.ca/~rneogi/event/combopt-group/stochastic-optimization') -->

<!-- {{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Wowchemy's [_Slides_](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).

Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page. -->
