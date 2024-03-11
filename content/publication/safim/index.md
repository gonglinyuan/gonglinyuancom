---
title: "Evaluation of LLMs on Syntax-Aware Code Fill-in-the-Middle Tasks"
authors:
- admin
- Sida Wang
- Mostafa Elhoushi
- Alvin Cheung
date: "2024-03-07T00:00:00Z"
doi:

# Schedule page publish date (NOT publication's date).
publishDate: "2024-03-07T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: We introduce Syntax-Aware Fill-In-the-Middle (SAFIM), a new benchmark for evaluating Large Language Models (LLMs) on the code Fill-in-the-Middle (FIM) task. This benchmark focuses on syntax-aware completions of program structures such as code blocks and conditional expressions, and includes 17,720 examples from multiple programming languages, sourced from recent code submissions after April 2022 to minimize data contamination. SAFIM provides a robust framework with various prompt designs and novel syntax-aware post-processing techniques, facilitating accurate and fair comparisons across LLMs. Our comprehensive evaluation of 15 LLMs shows that FIM pretraining not only enhances FIM proficiency but also improves Left-to-Right (L2R) inference using LLMs. Our findings challenge conventional beliefs and suggest that pretraining methods and data quality have more impact than model size. SAFIM thus serves as a foundational platform for future research in effective pretraining strategies for code LLMs. The evaluation toolkit and dataset are available at [https://github.com/gonglinyuan/safim](https://github.com/gonglinyuan/safim), and the leaderboard is available at [https://safimbenchmark.com/](https://safimbenchmark.com/).
# Summary. An optional shortened abstract.
summary: We introduce Syntax-Aware Fill-In-the-Middle (SAFIM), a new benchmark for evaluating Large Language Models (LLMs) on the code Fill-in-the-Middle (FIM) task.

tags: []
featured: true

url_pdf: https://arxiv.org/pdf/2403.04814
url_code: https://github.com/gonglinyuan/ast_t5
url_dataset: https://huggingface.co/datasets/gonglinyuan/safim
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
