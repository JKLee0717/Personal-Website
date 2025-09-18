---
title: 'True Impact of Cascade Length in Contextual Cascading Bandits'
authors:
- Hyunjun Choi
- admin
- Min-hwan Oh
# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-09-19T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-09-19T00:00:00Z' # "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: _Neural Information Processing Systems_ (__NeurIPS__), 2025 
publication_short: _NeurIPS_ 2025

abstract: We revisit the contextual cascading bandit, where a learning agent recommends an ordered list ($\text{\textit{cascade}}$) of items and a user scans the list sequentially, stopping at the first attractive item. Although cascading bandits underpin various search and recommendation engines, the role of the cascade length $K$ in shaping regret has remained ambiguous. Contrary to prior results that regret grows with $K$, we prove that in the contextual setting it actually $\text{\textit{decreases}}$ once $K$ is large enough. Leveraging this insight, we design a new upper-confidence-bound algorithm built on online mirror descent that attains the sharpest known regret upper bound, $\tilde{\mathcal{O}}\bigl(K\bar{p}^{K-1} d \sqrt{T}\bigr)$ for contextual cascading bandits. To complement this new regret upper bound, we match it with a lower bound of $\Omega \bigl(K\underline{p}^{K-1} d \sqrt{T}\bigr)$, where $0 \leq \underline{p} \leq \bar{p} < 1$. Together, these results fully characterize how regret truly scales with $K$ and close the theoretical gap for contextual cascading bandits. Finally, extensive experiments validate our theoretical results and show the effectiveness of our proposed method.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []
# - Source Themes
featured: false

# links:
# - name: Custom Link
#   url: http://example.org
# url_pdf: 'https://arxiv.org/pdf/2405.09831'  
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
