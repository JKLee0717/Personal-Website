---
title: 'Preference-based Reinforcement Learning beyond Pairwise Comparisons: Benefits of Multiple Options'
authors:
- admin
- Seouh-won Yi
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

abstract: We study online preference-based reinforcement learning (PbRL) with the goal of improving sample efficiency. While a growing body of theoretical work has emerged—motivated by PbRL’s recent empirical success, particularly in aligning large language models (LLMs)—most existing studies focus only on pairwise comparisons. A few recent works  [Zhu et al., 2023, Mukherjee et al., 2024, Thekumparampil et al., 2024]  have explored using multiple comparisons and ranking feedback, but their performance guarantees fail to improve—and can even deteriorate—as the feedback length increases, despite the richer information available. To address this gap, we adopt the Plackett–Luce (PL) model for ranking feedback over action subsets and propose **M-AUPO**, an algorithm that selects multiple actions by maximizing the average uncertainty within the offered subset. We prove that **M-AUPO** achieves a suboptimality gap of $\tilde{\mathcal{O}}\left( \frac{d}{T} \sqrt{ \sum_{t=1}^T \frac{1}{|S_t|}} \right)$, where $T$ is the total number of rounds, $d$ is the feature dimension, and $|S_t|$ is the size of the subset at round $t$. This result shows that larger subsets directly lead to improved performance and, notably, the bound avoids the exponential dependence on the unknown parameter’s norm, which was a fundamental limitation in most previous works. Moreover, we establish a near-matching lower bound of $\Omega \left( \frac{d}{K \sqrt{T}} \right)$, where $K$ is the maximum subset size. To the best of our knowledge, this is the first theoretical result in PbRL with ranking feedback that explicitly shows improved sample efficiency as a function of the subset size.

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
