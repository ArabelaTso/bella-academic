---
title: Understanding the Bug Characteristics and Fix Strategies of Federated Learning Systems

event: https://2023.esec-fse.org/
event_url: https://dl.acm.org/doi/10.1145/3611643.3616347

# location: Wowchemy HQ
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

summary: ESEC/FSE 23 Presentation
abstract: Federated learning (FL) is an emerging machine learning paradigm that aims to address the problem of isolated data islands. To preserve privacy, FL allows machine learning models and deep neural networks to be trained from decentralized data kept privately at individual devices. FL has been increasingly adopted in mission-critical fields such as finance and healthcare. However, bugs in FL systems are inevitable and may result in catastrophic consequences such as financial loss, inappropriate medical decision, and violation of data privacy ordinance. While many recent studies were conducted to understand the bugs in machine learning systems, there is no existing study to characterize the bugs arising from the unique nature of FL systems. To fill the gap, we collected 395 real bugs from six popular FL frameworks (Tensorflow Federated, PySyft, FATE, Flower, PaddleFL and Fedlearner) in GitHub and StackOverflow, and then manually analyzed their symptoms and impacts, prone stages, root causes and fix strategies, and report a series of findings and actionable implications. Finally, we provide possible suggestions or solutions for developers of FL systems based on the above findings and implications.


# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2023-12-07T11:30:00Z"
date_end: "2023-12-07T11:45:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate: "2017-01-01T00:00:00Z"

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
# url_code: ""
# url_pdf: ""
# url_slides: ""
# url_video: ""

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
# - example
---

<!-- {{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}
 -->
<!-- Slides can be added in a few ways: -->

<!-- - **Create** slides using Wowchemy's [*Slides*](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).

Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page. -->
