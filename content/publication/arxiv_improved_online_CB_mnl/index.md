---
title: 'Improved Online Confidence Bounds for Multinomial Logistic Bandits'
authors:
- admin
- Min-hwan Oh
# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-02-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-02-01T00:00:00Z' # "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: arXiv 
publication_short: arXiv

abstract: In this paper, we propose an improved online confidence bound for multinomial logistic (MNL) models and apply this result to MNL bandits, achieving variance-dependent optimal regret. Recently, Lee & Oh (2024) established an online confidence bound for MNL models and achieved nearly minimax-optimal regret in MNL bandits. However, their results still depend on the norm-boundedness of the unknown parameter $B$ and the maximum size of possible outcomes $K$. To address this, we first derive an online confidence bound of $\mathcal{O}\left(\sqrt{d \log t} + B \right)$, which is a significant improvement over the previous bound of $\mathcal{O} (B \sqrt{d} \log t \log K )$ (Lee & Oh, 2024). This is mainly achieved by establishing tighter self-concordant properties of the MNL loss and introducing a novel intermediary term to bound the estimation error. Using this new online confidence bound, we propose a constant-time algorithm, $\texttt{OFU-MNL++}$, which achieves a variance-dependent regret bound of $\mathcal{O} \Big( d \log T \sqrt{ \smash[b]{\sum_{t=1}^T} \sigma_t^2 } \Big) $ for sufficiently large $T$, where $\sigma_t^2$ denotes the variance of the rewards at round $t$, $d$ is the dimension of the contexts, and $T$ is the total number of rounds.Furthermore, we introduce a Maximum Likelihood Estimation (MLE)-based algorithm, $\texttt{OFU-M^2NL}$, which achieves an anytime $\operatorname{poly}(B)$-free regret of $\mathcal{O} \Big( d \log (BT) \sqrt{ \smash[b]{\sum_{t=1}^T} \sigma_t^2 } \Big) $.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []
# - Source Themes
featured: false

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: 'https://arxiv.org/pdf/2502.10020'
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
