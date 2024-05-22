---
title: 'Nearly Minimax Optimal Regret for Multinomial Logistic Bandit'
authors:
- admin
- Min-hwan Oh
# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-05-17T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-05-17T00:00:00Z' # "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: __arXiv__, 2024 
publication_short: _arXiv_ 2024

abstract: In this paper, we study the contextual multinomial logit (MNL) bandit problem in which a learning agent sequentially selects an assortment based on contextual information, and user feedback follows an MNL choice model. There has been a significant discrepancy between lower and upper regret bounds, particularly regarding the feature dimension $d$ and the maximum assortment size $K$. Additionally, the variation in reward structures between these bounds complicates the quest for optimality. Under uniform rewards, where all items have the same expected reward, we establish a regret lower bound of $\Omega(d\sqrt{\smash[b]{T/K}})$ and propose a constant-time algorithm, OFU-MNL+, that achieves a matching upper bound of $\tilde{\mathcal{O}}(d\sqrt{\smash[b]{T/K}})$. Under non-uniform rewards, we prove a lower bound of $\Omega(d\sqrt{T})$ and an upper bound of $\tilde{\mathcal{O}}(d\sqrt{T})$, also achievable by OFU-MNL+. Our empirical studies support these theoretical findings. To the best of our knowledge, this is the first work in the contextual MNL bandit literature to prove minimax optimality --- for either uniform or non-uniform reward setting --- and to propose a computationally efficient algorithm that achieves this optimality up to logarithmic factors.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []
# - Source Themes
featured: false

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: 'https://arxiv.org/pdf/2405.09831'
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
