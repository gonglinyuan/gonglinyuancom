---
title: 'Anytime Sampling for Autoregressive Models via Ordered Autoencoding'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yilun Xu
  - Yang Song
  - Sahaj Garg
  - admin
  - Rui Shu
  - Aditya Grover
  - Stefano Ermon

# Author notes (optional)
author_notes:

date: '2021-02-23T00:00:00Z'
doi:

# Schedule page publish date (NOT publication's date).
publishDate: '2021-02-23T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In International Conference on Learning Representations 2021
publication_short: In ICLR 2021

abstract: Autoregressive models are widely used for tasks such as image and audio generation. The sampling process of these models, however, does not allow interruptions and cannot adapt to real-time computational resources. This challenge impedes the deployment of powerful autoregressive models, which involve a slow sampling process that is sequential in nature and typically scales linearly with respect to the data dimension.  To address this difficulty, we propose a new family of autoregressive models that enables anytime sampling. Inspired by Principal Component Analysis, we learn a structured representation space where dimensions are ordered based on their importance with respect to reconstruction. Using an autoregressive model in this latent space, we trade off sample quality for computational efficiency by truncating the generation process before decoding into the original data space. Experimentally, we demonstrate in several image and audio generation tasks that sample quality degrades gracefully as we reduce the computational budget for sampling. The approach suffers almost no loss in sample quality (measured by FID) using only 60\% to 80\% of all latent dimensions for image data. Code is available at [https://github.com/Newbeeer/Anytime-Auto-Regressive-Model](https://github.com/Newbeeer/Anytime-Auto-Regressive-Model).
# Summary. An optional shortened abstract.
summary: We propose a new family of autoregressive model that enables anytime sampling.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2102.11495.pdf'
url_code: 'https://github.com/Newbeeer/Anytime-Auto-Regressive-Model'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://www.dropbox.com/scl/fi/54d9y4h6pjrxrc5fs2ftf/anytime_paper.pptx?dl=0&rlkey=n1wkz5y47pwdzde2hbdwptatr'
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
