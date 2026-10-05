---
title: "When Masking Preimage Computation Isn’t Enough: A Power Analysis Attack on Masked Implementations of Falcon"
authors:
- admin
date: "2026-10-04"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-10-05T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "[Cryptology ePrint Archive](https://eprint.iacr.org/)"
publication_short: "ePrint"

abstract: "In this paper, we present a novel power analysis attack targeting a Falcon implementation protected by a masked preimage computation. By analyzing the ratio between the real and imaginary parts of the public hash polynomial, we demonstrate that the leakage during the share recombination phase can be exploited to recover the secret key. We propose two attack variants: a chosen-message attack, where the adversary controls input messages to force extreme coefficient ratios, and a non-chosen-message attack that filters for naturally occurring vulnerable hashes. Through experimental evaluations using the ELMO leakage simulator for an ARM Cortex-M0 architecture, our experiments achieve a 98.3% success rate with 4,000 traces. Finally, while a fully masked implementation of Falcon prevents our attack, we propose a practical countermeasure based on rejection sampling to avoid the prohibitive computational overhead of a fully masked Gaussian sampler."

# Summary. An optional shortened abstract.
summary: "In this paper, we provide a side-channel attack on Falcon with masked preimage computation. Our attack targets the complex product by analyzing the ratio between the real and imaginary parts of the public hash polynomial. We also provide a lightweight countermeasure to resist this type of attack."

tags:
- Side-Channel Analysis

featured: true

links:
- name: 'DOI'
  url: 'https://eprint.iacr.org/2026/2313'
url_pdf: 'https://eprint.iacr.org/2026/2313.pdf'
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
