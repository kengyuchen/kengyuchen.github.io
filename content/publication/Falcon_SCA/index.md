---
title: "When Masking Multiplication Isn’t Enough: Exploiting Floating-Point Leakage in Falcon’s Pre-Image Computation"
authors:
- admin
- Ming Qing Ching
- Jiun-Peng Chen
- Bo-Yin Yang
date: "2026-1-15"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-04-04T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "[IACR Transactions on Cryptographic Hardware and Embedded Systems (TCHES)](https://tches.iacr.org/)"
publication_short: "TCHES"

abstract: In this paper, we present an improved correlation power analysis (CPA) attack on the pre-image computation of the digital signature scheme Falcon. Our attack exploits new side-channel leakage that multiplication masking schemes fail to protect. To enhance both the efficiency and accuracy of the attack, we develop new theoretical insights for recovering the secret floating-point numbers, which can also be leveraged to improve prior attacks. For mantissa recovery, we identify and correct a flaw in an earlier work and provide a more complete and practical analysis. For exponent recovery, we analyze the distribution of Falcon’s secret key after the fast Fourier transform, reduce the number of required traces, and mitigate false positives. To validate our attack, we conducted two experiments targeting existing countermeasures on floating-point multiplication. In our environment, we successfully recovered the secret key using only around one thousand power traces. Our results demonstrate that protecting floating-point multiplication alone is insufficient to defend Falcon against side-channel attacks. A comprehensive masking including at least floating-point addition is necessary.

# Summary. An optional shortened abstract.
summary: "In this paper, we provide an improved side-channel attack on the pre-image computation of Falcon. Our attack targets the implementation that only protects the floating-point multiplication. We show that protecting floating-point multiplication alone is insufficient to defend Falcon against side-channel attacks."

tags:
- Side-Channel Analysis

featured: true

links:
#- name: 'DOI'
#  url: 'https://tches.iacr.org/index.php/TCHES/article/view/11428'
url_pdf: ''
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
