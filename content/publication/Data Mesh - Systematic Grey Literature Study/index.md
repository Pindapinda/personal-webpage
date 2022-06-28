---
title: "Data Mesh"
subtitle: "Systematic Gray Literature Study, Reference Architecture, and Cloud-based Instantiation at ASML"
share: false

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Abel Goedgebuure
# - admin

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2022-06-28T00:00:00Z"
# doi: "https://doi.org/10.48550/arXiv.2102.08864"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-06-28T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: Thesis
publication_short: Thesis

abstract: To no surprise, it recently has become the norm for organizations to become data-driven. As the world continues to digitize, new opportunities arise that organizations are trying to capitalize on. Becoming data-driven allows organizations to use novel business models, develop new digital products, and make better decisions. However, becoming data-driven is not as easy as it sounds. Although there have been incredible innovations concerning the storing and processing of large amounts of data, organizations struggle with unlocking the true potential of their data.

Traditional big data architectures, such as data warehouses or data lakes, consist of centralized technical solutions to store vast amounts of data. A centralized team provisions the data by building data pipelines that transform the data into the desired format and serve it to consumers all across the organization. This imposes several challenges to the organization. First of all, the capacity of this centralized team becomes the bottleneck of data sharing in the entire organization. Furthermore, since the centralized team is separated from the business domains providing and consuming the data, it becomes difficult to serve high-quality data in line with the consumer's needs. Moreover, this centralized team's many point-to-point data pipelines become challenging to oversee and manage as their number increases. This removes all agility from the organization resulting in a large and monolithic data landscape. Additionally, data becomes challenging to govern since there is no clear ownership of data.

Data mesh, a novel data architecture paradigm, attempts to address these challenges. Data Mesh is a decentralised data architecture in which business domains themselves become responsible for serving their data as a product to the organization. These domains are supported by a self-serve infrastructure platform that abstracts away the complexities of managing the infrastructure necessary to serve data as a product. Moreover, it uses a federated computational governance model in which governance responsibilities are distributed to the business domains. However, there is a gap between industry practice and academic research. No academic literature is available yet, while the industry is already adopting the data mesh paradigm. This thesis addresses this gap by conducting a systematic gray literature review that defines data mesh and its requirements. Moreover, the design science research methodology for information systems is used to incorporate these findings into a reference architecture for data mesh. Additionally, the thesis delivers an instantiation of the architecture on a public cloud provider, and the design artifacts are demonstrated in an illustrative use case at ASML. All results are validated through expert interviews with senior stakeholders from the industry.

# Summary. An optional shortened abstract.
summary: A master thesis on data mesh based on gray literature. This thesis will be published as a set-alone paper in future.

tags: [Data Mesh, Reference Architecture, Design Patterns, Literature Study]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

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
  caption: 'The content of the Thesis'
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
