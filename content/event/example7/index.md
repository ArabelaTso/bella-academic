---
title: 基于大模型的需求描述到形式化规约生成初探 (A Preliminary Study on the Generation of Formal Specifications from Requirements Description Based on Large Language Model）

event: https://mp.weixin.qq.com/s/gVCc2whHnXoSu2wUeU15qA
event_url: https://mp.weixin.qq.com/s/gVCc2whHnXoSu2wUeU15qA

# location: Wowchemy HQ
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

summary: 2024 CCF形式化方法专委会战略研讨会—形式化方法与人工智能的交叉融合：机遇与挑战 (Cross-integration of formal methods and artificial intelligence - opportunities and challenges)
abstract: 随着形式化方法在软件质量保证过程中的重要性日益凸显，将自然语言描述转化为形式化规约、最终完成形式化验证的自动化过程成为了一个关键的研究课题。本报告初步探讨了基于大语言模型的从自然语言描述到形式化规约生成、最后到验证的自动化转换流程，旨在缩小需求描述与形式化规约之间的鸿沟。我们首先探索了大语言模型如ChatGPT-3.5、通义千问、DeepSeek、StarCoder等在形式化规约生成上的初始能力，并探索提示工程 (prompt engineering) 及上下文学习(in-context learning) 的提升上限。接着通过小样本学习（few-shot learning）及思维链（Chain-of-Thought）等方式进行尝试，识别出更利于规约生成的识别方式。最后，我们构建了1000+高质量的“描述-规约”对，通过对DeepSeek进行监督微调（Supervised Fine-Tuning），使得微调后的模型在两种规约语言生成上达到显著提升。最后，通过一系列案例研究，我们展示了大语言模型在捕捉自然语言描述的语义及生成符合形式化验证标准的规约方面的潜力。此外，报告还讨论了在转换过程中面临的挑战，包括需求描述中的歧义解析、转换准确性的验证等。最后，我们展望了基于大语言模型的需求到规约生成技术的未来挑战及发展方向。


# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2024-05-05T09:00:00Z"
date_end: "2024-05-05T17:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate: "2017-01-01T00:00:00Z"

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: true

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

