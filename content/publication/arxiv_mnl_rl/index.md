---
title: 'Randomized Exploration for Reinforcement Learning with Multinomial Logistic Function Approximation'
authors:
- Wooseong Cho
- Taehyun Hwang
- admin
- Min-hwan Oh
# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-05-31T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-12-15T00:00:00Z' # "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: _Neural Information Processing Systems_(__NeurIPS__), 2024 
publication_short: _NeurIPS_ 2024

abstract: We study reinforcement learning with *multinomial logistic* (MNL) function approximation where the underlying transition probability kernel of the *Markov decision processes* (MDPs) is parametrized by an unknown transition core with features of state and action. For the finite horizon episodic setting with inhomogeneous state transitions, we propose provably efficient algorithms with randomized exploration having frequentist regret guarantees. For our first algorithm, $\texttt{RRL-MNL}$, we adapt optimistic sampling to ensure the optimism of the estimated value function with sufficient frequency and establish that $\texttt{RRL-MNL}$ is both *statistically* and *computationally* efficient, achieving a $\tilde{\mathcal{O}}(\kappa^{-1} d^{\frac{3}{2}} H^{\frac{3}{2}} \sqrt{T})$ frequentist regret bound with constant-time computational cost per episode. Here, $d$ is the dimension of the transition core, $H$ is the horizon length, $T$ is the total number of steps, and $\kappa$ is a problem-dependent constant. Despite the simplicity and practicality of $\texttt{RRL-MNL}$, its regret bound scales with $\kappa^{-1}$, which is potentially large in the worst case. To improve the dependence on $\kappa^{-1}$, we propose $\texttt{ORRL-MNL}$, which estimates the value function using local gradient information of the MNL transition model. We show that its frequentist regret bound is $\tilde{\mathcal{O}}(d^{\frac{3}{2}} H^{\frac{3}{2}} \sqrt{T} + \kappa^{-1} d^2 H^2)$. To the best of our knowledge, these are the first randomized RL algorithms for the MNL transition model that achieve both computational and statistical efficiency. Numerical experiments demonstrate the superior performance of the proposed algorithms.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []
# - Source Themes
featured: false

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: 'https://arxiv.org/pdf/2405.20165'
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
