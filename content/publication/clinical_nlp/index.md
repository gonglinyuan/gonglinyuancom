---
title: "Improved Clinical Abbreviation Expansion via Non-Sense-Based Approaches"
authors:
- Juyong Kim
- admin
- Justin Khim
- Jeremy C. Weiss
- Pradeep Ravikumar
date: "2020-11-23T00:00:00Z"
doi:

# Schedule page publish date (NOT publication's date).
publishDate: "2020-11-23T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

publication: In Machine Learning for Health NeurIPS Workshop 2020
publication_short: In ML4H (NeurIPS Workshop) 2020

abstract: Abbreviation expansion is an important problem in clinical natural language processing because abbreviations often occur in text notes in medical records, and expansions of these abbreviations are critical for downstream applications such as assistive diagnosis and insurance code review. Previous studies have treated abbreviation expansion as a special case of word sense disambiguation; however, abbreviation expansion is easier because we only need the character level expansion and not necessarily the full sense of the abbreviation. In particular, such character level expansions may naturally occur elsewhere in medical contexts. Accordingly, we consider two categories of methods for abbreviation expansion:(a) non-sense-based methods that use information solely at lexical levels using state-of-the-art language models, and (b) sense-based methods that also incorporate sense information, such as glosses, from knowledge bases, to simultaneously perform the two tasks of expansion and disambiguation of the abbreviation. We propose two language model based approaches, including a novel length-agnostic permutation language model, find non-sense methods to be more effective than sense-based methods, and achieve the state-of-theart on three clinical datasets.

# Summary. An optional shortened abstract.
summary: We propose two language model based approaches, including a novel length-agnostic permutation language model, find non-sense methods to be more effective than sense-based methods.

tags: []
featured: false

url_pdf: http://proceedings.mlr.press/v136/kim20a/kim20a.pdf
url_code: https://github.com/dalgu90/abbr-exp-ml4h/
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---
