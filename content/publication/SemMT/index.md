---
title: "SemMT: A Semantic-based Testing Approach for Machine Translation Systems"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Jialun CAO
- Meiziniu LI
- Yeting LI
- Ming WEN
- Shing-Chi CHEUNG

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2020-12-03"
doi: "https://arxiv.org/abs/2012.01815"

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *arXiv*
publication_short: In *arXiv*

abstract: Machine translation has wide applications in daily life. In mission-critical applications such as translating official documents, incorrect translation can have unpleasant or sometimes catastrophic consequences. This motivates recent research on testing methodologies for machine translation systems. Existing methodologies mostly rely on metamorphic relations designed at the textual level (e.g., Levenshtein distance) or syntactic level (e.g., the distance between grammar structures) to determine the correctness of translation results. However, these metamorphic relations do not consider whether the original and translated sentences have the same meaning (i.e., Semantic similarity). Therefore, in this paper, we propose SemMT, an automatic testing approach for machine translation systems based on semantic similarity checking. SemMT applies round-trip translation and measures the semantic similarity between the original and translated sentences. Our insight is that the semantics expressed by the logic and numeric constraint in sentences can be captured using regular expressions (or deterministic finite automata) where efficient equivalence/similarity checking algorithms are available. Leveraging the insight, we propose three semantic similarity metrics and implement them in SemMT. The experiment result reveals SemMT can achieve higher effectiveness compared with state-of-the-art works, achieving an increase of 21% and 23% on accuracy and F-Score, respectively. We also explore potential improvements that can be achieved when proper combinations of metrics are adopted. Finally, we discuss a solution to locate the suspicious trip in round-trip translation, which may shed lights on further exploration.

# Summary. An optional shortened abstract.
summary: SemMT, a semantic-smilarity based translation testing framework

tags: ["Machine Tranlsation Testing", "DNN testing"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2012.01815.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://github.com/ArabelaTso/Learning-Based-ParaVerifer'
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
- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
