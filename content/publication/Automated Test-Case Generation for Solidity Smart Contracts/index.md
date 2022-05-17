---
title: "Automated Test-Case Generation for Solidity Smart Contracts"
subtitle: "The AGSolT Approach and its Evaluation"
share: false

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Dario Di Nucci
- Geert Monsieur
- Willem-Jan van den Heuvel

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-02-17T00:00:00Z"
doi: "https://doi.org/10.48550/arXiv.2102.08864"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-10-18T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *arXiv*
publication_short: In *arXiv*

abstract: Blockchain and smart contract technology are novel approaches to data and code management that facilitate trusted computing by allowing for development in a distributed and decentralized manner. Testing smart contracts comes with its own set of challenges which have not yet been fully identified and explored. Although existing tools can identify and discover known vulnerabilities and their interactions on the Ethereum blockchain through random search or symbolic execution, these tools generally do not produce test suites suitable for human oracles. In this paper, we present AGSOLT (Automated Generator of Solidity Test Suites). We demonstrate its efficiency by implementing two search algorithms to automatically generate test suites for stand-alone Solidity smart contracts, taking into account some of the blockchain-specific challenges. To test AGSOLT, we compared a random search algorithm and a genetic algorithm on a set of 36 real-world smart contracts. We found that AGSOLT is capable of achieving high branch coverage with both approaches and even discovered some errors in some of the most popular Solidity smart contracts on Github.

# Summary. An optional shortened abstract.
summary: A tool for automatically generating test suites that are optimised for branch coverage.

tags: [Blockchain, Smart Contracts, Automated Testing]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://link.springer.com/chapter/10.1007/978-3-030-76352-7_1'
url_code: 'https://github.com/AGSolT/SolAT'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'The flowchart of the AGSolT Tool'
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
---

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
