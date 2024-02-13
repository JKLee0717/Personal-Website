---
title: "Combinatorial Neural Bandits"
authors:
- admin
- Kyuwook Chai
- Min-hwan Oh
# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2023-04-26T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-04-26T00:00:00Z' # "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: _International Conference on Machine Learning_ (__ICML__), 2023
publication_short: _ICML_ 2023

abstract: We consider a contextual combinatorial bandit problem where in each round a learning agent selects a subset of arms and receives feedback on the selected arms according to their score. The score of an arm is an unknown function of the arm's feature. Approximating this unknown score function with deep neural networks, we propose algorithms$:$ Combinatorial Neural UCB ($\texttt{CN-UCB}$) and Combinatorial Neural Thompson Sampling ($\texttt{CN-TS}$). We prove that $\texttt{CN-UCB}$ achieves $\tilde{\mathcal{O}}(\tilde{d} \sqrt{T})$ or $\tilde{\mathcal{O}}(\sqrt{\tilde{d} T K})$ regret, where $\tilde{d}$ is the effective dimension of a neural tangent kernel matrix, $K$ is the size of a subset of arms, and $T$ is the time horizon. For $\texttt{CN-TS}$, we adapt an optimistic sampling technique to ensure the optimism of the sampled combinatorial action, establish a worst-case (frequentist) regret of $\tilde{\mathcal{O}}(\tilde{d} \sqrt{TK})$. To the best of our knowledge, these are the first combinatorial neural bandit algorithms with regret performance guarantees. In particular, $\texttt{CN-TS}$ is the first Thompson sampling algorithm with the worst-case regret guarantees for the general contextual combinatorial bandit problem. The numerical experiments demonstrate the superior performances of our proposed algorithms.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []
# - Source Themes
featured: false

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: 'https://openreview.net/pdf?id=vDyKXNQrKL'
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
