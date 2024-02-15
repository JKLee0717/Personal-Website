---
title: 'Demystifying Linear MDPs and Novel Dynamics Aggregation Framework'
authors:
- admin
- Min-hwan Oh
# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-01-16T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-02-15T00:00:00Z' # "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: _International Conference on Learning Representations_ (__ICLR__), 2024
publication_short: _ICLR_ 2024

abstract: In this paper, we first challenge the common premise that linear MDPs always induce performance guarantees independent of the state space. We prove that, in linear MDPs, the feature dimension $d$ is lower bounded by $S/U$ in order to aptly represent transition probabilities, where $S$ is the size of the state space and $U$ is the maximum size of directly reachable states. Hence, $d$ can still scale with $S$ depending on the direct reachability of the environment. To address this limitation of linear MDPs, we propose a novel structural aggregation framework based on dynamics, named as the $\textit{dynamics aggregation}$. For this newly proposed framework, we design a provably efficient hierarchical reinforcement learning algorithm in linear function approximation that leverages aggregated sub-structures. Our proposed algorithm exhibits statistical efficiency, achieving a regret of $\tilde{\mathcal{O}}  \big( d_{\psi}^{3/2} H^{3/2}\sqrt{ N T} \big)$, where $d_{\psi}$ represents the feature dimension of $\textit{aggregated subMDPs}$ and $N$ signifies the number of aggregated subMDPs. We establish that the condition $d_{\psi}^3 N \ll d^{3}$ is readily met in most real-world environments with hierarchical structures, enabling a substantial improvement in the regret bound compared to $\texttt{LSVI-UCB}$, which enjoys a regret of $\tilde{\mathcal{O}} (d^{3/2} H^{3/2} \sqrt{ T})$. To the best of our knowledge, this work presents the first HRL algorithm with linear function approximation that offers provable guarantees.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []
# - Source Themes
featured: false

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: 'https://openreview.net/pdf?id=RDSj6S8WJe'
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
