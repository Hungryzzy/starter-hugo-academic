---
title: 'Minimax Decision Trees via Martingale Approximations'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Hengrui Luo

date: '2025-02-01T00:00:00Z'
doi: ''

weight: 83

# Schedule page publish date (NOT publication's date).
publishDate: '2025-02-01T00:00:00Z'

# # Publication type.
# # Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# # 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# # 7 = Thesis; 8 = Patent
# publication_types: ['1']

# # Publication name and optional abbreviated publication name.
# publication: In *Wowchemy Conference*
# publication_short: In *ICW*

abstract: 'We develop a martingale-based approach to constructing decision trees that efficiently approximate a target variable through recursive conditioning. We introduce MinimaxSplit, a novel splitting criterion that minimizes the worst-case variance at each step, and analyze its cyclic variant, proving an exponential error decay rate under mild conditions. Our analysis builds upon partition-based martingale approximations, providing new insights into their convergence behavior. Unlike traditional variance-based methods, MinimaxSplit avoids end-cut preference and performs well in noisy settings. We derive empirical risk bounds and also explore its integration into random forests.'

# Summary. An optional shortened abstract.
summary: In submission, 2025+

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: PDF
  url: uploads/tree.pdf
- name: ArXiv
  url: https://arxiv.org/abs/2502.16758



url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
