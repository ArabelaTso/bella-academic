---
title: "L-CMP: an automatic learning-based parameterized verification tool."

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Yeting LI
- Zhiwu XU
- Jialun CAO
- Haiming CHEN
- Tingjian GE
- Shing-Chi CHEUNG
- Haoren ZHAO

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2020-12-21"
doi: "hhttps://dl.acm.org/doi/10.1145/3324884.3416556"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 35th IEEE/ACM International Conference on Automated Software Engineering*
publication_short: In *ASE*

abstract: Regular expressions (regexes) are widely used in different fields of computer science such as programming languages, string processing and databases. However, existing tools for synthesizing or repairing regexes were not designed to be resilient to Regex Denial of Service (ReDoS) attacks. Specifically, if a regex has super-linear (SL) worst-case complexity, an attacker could provide carefully-crafted inputs to launch ReDoS attacks. Therefore, in this paper, we propose a programming-by-example framework, FlashRegex, for generating anti-ReDoS regexes by either synthesizing or repairing from given examples. It is the first framework that integrates regex synthesis and repair with the awareness of ReDoS-vulnerabilities. We present novel algorithms to deduce anti-ReDoS regexes by reducing the ambiguity of these regexes and by using Boolean Satisfiability (SAT) or Neighborhood Search (NS) techniques. We evaluate FlashRegex with five related state-of-the-art tools. The evaluation results show that our work can effectively and efficiently generate anti-ReDoS regexes from given examples, and also reveal that existing synthesis and repair tools have neglected ReDoS-vulnerabilities of regexes. Specifically, the existing synthesis and repair tools generated up to 394 ReDoS-vulnerable regex within few seconds to more than one hour, while FlashRegex generated no SL regex within around five seconds. Furthermore, the evaluation results on ReDoS-vulnerable regex repair also show that FlashRegex has better capability than existing repair tools and even human experts, achieving 4 more ReDoS-invulnerable regex after repair without trimming and resorting, highlighting the usefulness of FlashRegex in terms of the generality, automation and user-friendliness.
# Summary. An optional shortened abstract.
summary: FlashRegex, for generating anti-ReDoS regexes.

tags: ["ReDoS"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Project
  # url: 

url_pdf: 'https://dl.acm.org/doi/pdf/10.1145/3324884.3416556'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/i2sY9HwR-Uc'

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
projects:
- []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: "" #example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
