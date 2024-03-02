---
title: "ADELT: Transpilation Between Deep Learning Frameworks"
authors:
- admin
- Jiayi Wang
- Alvin Cheung
date: "2023-03-07T00:00:00Z"
doi:

# Schedule page publish date (NOT publication's date).
publishDate: "2023-03-07T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: We propose Adversarial DEep Learning Transpiler (ADELT) for source-to-source transpilation between deep learning frameworks. Unlike prior approaches, we decouple the transpilation of code skeletons and the mapping of API keywords (an API function name or a parameter name). ADELT transpile code skeletons using few-shot prompting on big language models. Based on contextual embeddings extracted by a BERT for code, we train aligned API embeddings in a domain-adversarial setup, upon which we generate a dictionary for keyword translation. The model is trained on our unlabeled DL corpus from web crawl data, without using any hand-crafted rules and parallel data. Our method outperforms state-of-the-art transpilers on multiple transpilation pairs including PyTorch-Keras and PyTorch-MXNet by 15.9pts and 12.0pts in exact match scores respectively.

# Summary. An optional shortened abstract.
summary: We propose a transpiler across deep learning frameworks using LLM and adversarial learning techniques.

tags: []
featured: false

url_pdf: https://arxiv.org/pdf/2303.03593.pdf
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
