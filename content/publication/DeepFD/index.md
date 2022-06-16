---
title: "DeepFD: Automated Fault Diagnosis and Localization for Deep Learning Programs"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Jialun CAO
- Meiziniu LI
- Xiao CHEN
- Yongqiang TIAN
- Ming WEN
- Bo WU
- Shing-Chi CHEUNG

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2022-05-21"
doi: "https://doi.org/10.1145/3510003.3510099"

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE/ACM 43rd International Conference on Software Engineering*
publication_short: In *ICSE*

abstract: As Deep Learning (DL) systems are widely deployed for mission-critical applications, debugging such systems becomes essential. Most existing works identify and repair suspicious neurons on the trained Deep Neural Network (DNN), which, unfortunately, might be a detour. Specifically, several existing studies have reported that many unsatisfactory behaviors are actually originated from the faults residing in DL programs. Besides, locating faulty neurons is not actionable for developers, while locating the faulty statements in DL programs can provide developers with more useful information for debugging. Though a few recent studies were proposed to pinpoint the faulty statements in DL programs or the training settings (e.g. too large learning rate), they were mainly designed based on predefined rules, leading to many false alarms or false negatives, especially when the faults are beyond their capabilities. In view of these limitations, in this paper, we proposed DeepFD, a learning-based fault diagnosis and localization framework which maps the fault localization task to a learning problem. In particular, it infers the suspicious fault types via monitoring the runtime features extracted during DNN model training and then locates the diagnosed faults in DL programs. It overcomes the limitations by identifying the root causes of faults in DL programs instead of neurons and diagnosing the faults by a learning approach instead of a set of hard-coded rules. The evaluation exhibits the potential of DeepFD. It correctly diagnoses 52% faulty DL programs, compared with around half (27%) achieved by the best state-of-the-art works. Besides, for fault localization, DeepFD also outperforms the existing works, correctly locating 42% faulty programs, which almost doubles the best result (23%) achieved by the existing works.

# Summary. An optional shortened abstract.
summary: DeepFD, a learning-based fault diagnosis and localization framework which maps the fault localization task to a learning problem.

tags: ["DL testing", "DL Debugging", "DL Fault Localization"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2205.01938.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://github.com/ArabelaTso/DeepFD'
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/VbFbhBa6Ot4'

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
