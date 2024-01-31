---
title: Testing Coreference Resolution Systems without Labeled Test Sets

event: https://2023.esec-fse.org/
event_url: https://dl.acm.org/doi/10.1145/3611643.3616258

# location: Wowchemy HQ
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

summary: ESEC/FSE 23 Presentation
abstract: Coreference resolution (CR) is a task to resolve different expressions (e.g., named entities, pronouns) that refer to the same real-world en- tity/event. It is a core natural language processing (NLP) component that underlies and empowers major downstream NLP applications such as machine translation, chatbots, and question-answering. De- spite its broad impact, the problem of testing CR systems has rarely been studied. A major difficulty is the shortage of a labeled dataset for testing. While it is possible to feed arbitrary sentences as test inputs to a CR system, a test oracle that captures their expected test outputs (coreference relations) is hard to define automatically. To address the challenge, we propose Crest, an automated testing methodology for CR systems. Crest uses constituency and depen- dency relations to construct pairs of test inputs subject to the same coreference. These relations can be leveraged to define the meta- morphic relation for metamorphic testing. We compare Crest with five state-of-the-art test generation baselines on two popular CR systems, and apply them to generate tests from 1,000 sentences randomly sampled from CoNLL-2012, a popular dataset for corefer- ence resolution. Experimental results show that Crest outperforms baselines significantly. The issues reported by Crest are all true positives (i.e., 100% precision), compared with 63% to 75% achieved by the baselines.


# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2023-12-05T11:45:00Z"
date_end: "2023-12-05T12:00:00Z"
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
