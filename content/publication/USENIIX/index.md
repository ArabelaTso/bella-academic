---
title: "ReDoSHunter: A Combined Static and Dynamic Approach for Regular Expression DoS Detection."

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Yeting LI
- Zixuan CHEN
- Jialun CAO
- Zhiwu XU
- Qiancheng Peng
- Haiming CHEN
- Liyuan CHEN
- Shing-Chi CHEUNG

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-08-11"
doi: "https://dl.acm.org/doi/10.1145/3324884.3416556"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *USENIX Security Symposium*
publication_short: In *USENIX Security*

abstract: Regular expression Denial of Service (ReDoS) is a class ofalgorithmic complexity attacks using the regular expressions(regexes) that cause the typical backtracking-based match-ing  algorithms  to  run  super-linear time.  Due  to  the  wideadoption of regexes in computation, ReDoS poses a perva-sive and serious security threat. Early detection of ReDoS-vulnerable regexes in software is thus vital. Existing detectionapproaches mainly fall into two categories - static and dynamicanalysis. However, they all suffer from either poor precisionor poor recall in the detection of vulnerable regexes.  Theproblem of accurately detecting vulnerable regexes at highprecision and high recall remains unsolved. Furthermore, weobserved that many ReDoS-vulnerable regex contain morethan one vulnerability in reality. Another problem with exist-ing approaches is that they are incapable of detecting multiplevulnerabilities in one regex. To address these two problems, we propose ReDoSHunter,a ReDoS-vulnerable regex detection framework that can effectively pinpoint the multiple vulnerabilities in a vulnerableregex, and generate examples of attack-triggering strings. Re-DoSHunter is driven by five vulnerability patterns derivedfrom massive vulnerable regexes. Besides pinpointing vulner-abilities, ReDoSHunter can assess the degree (i.e., exponentialor polynomial) of the vulnerabilities detected. Our experi-ment results show that ReDoSHunter achieves 100% preci-sion and 100% recall in the detection of ReDoS-vulnerableregexes in three large-scale datasets with 37,651 regexes. Itsignificantly outperforms seven state-of-the-art techniques.ReDoSHunter uncovered 28 new ReDoS-vulnerabilities in26 well-maintained popular projects, resulting in 26 assignedCVEs and 2 fixes.
# Summary. An optional shortened abstract.
summary: ReDoSHunter, a ReDoS-vulnerable regex detection framework that can effectively pinpoint the multiple vulnerabilities in a vulnerableregex

tags: ["ReDoS"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Project
  # url: 

url_pdf: 'https://arxiv.org/pdf/2012.01815.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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
