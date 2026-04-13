---
title: "The Cryptographic Layer of Biometric Authentication"
authors:
- admin
- Serge Vaudenay
date: ""
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-04-13"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# Options: article-journal, paper-conference, thesis, book, chapter, report, patent, manuscript
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "[Applied Cryptography and Network Security 2026](https://acns2026.github.io/)"
publication_short: "ACNS"

abstract: "In this paper, we focus on the cryptographic layer for biometric authentication. The layer is added on the top of an authentication scheme for security and privacy reasons. We first formalize a biometric authentication scheme and propose security models for two security properties of interest: unforgeability and indistinguishability. Unforgeability refers to an adversary’s ability to impersonate a user, while indistinguishability evaluates an adversary’s knowledge of users’ biometrics, related to privacy preservation. We then introduce generic constructions using a digital signature scheme and a public-key encryption scheme to achieve the two security properties, respectively. To overcome the limitations of these generic constructions, we further analyze existing instantiations of biometric authentication built on the cryptographic primitives: function-hiding inner product functional encryption. Our results demonstrate conditions for the biometrics and the cryptographic instantiations under which these schemes achieve security within our security model."

# Summary. An optional shortened abstract.
summary: "In this paper, we provide a framework for analyzing the security of biometric authentication schemes. We formalize two security properties, unforgeability and indistinguishability, and propose generic constructions. We also analyze existing instantiations based on function-hiding inner product functional encryption, demonstrating conditions for achieving security within our model."

tags:
- Biometric Authentication
- Functional Encryption

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
