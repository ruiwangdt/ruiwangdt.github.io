---
title: A Probabilistic Generative Method for Safe Physical System Control Problems
authors:
- Peiyan Hu
- Xiaowei Qian
- Wenhao Deng
- admin
- Haodong Feng
- Ruiqi Feng
- Tao Zhang
- Long Wei
- Yue Wang
- Zhi-Ming Ma
- Tailin Wu
date: -01-01
publishDate: '2024-11-25T15:14:37.243347Z'
publication_types:
- paper-conference
publication: NeurIPS Safe Generative AI Workshop 2024

abstract: Controlling complex physical systems is a crucial task in science and engineering, often requiring the balance of control objectives and safety constraints. Recently, diffusion models have demonstrated a strong ability to model high-dimensional state spaces, giving them an advantage over recent deep learning and reinforcement learning-based methods in complex control tasks. However, they do not inherently address safety concerns. In contrast, while safe reinforcement learning methods consider safety, they typically fail to provide guarantees for satisfying safety constraints. To address these limitations, we propose Safe Conformal Physical system control (SafeConPhy), which optimizes the diffusion model with a provable safety bound iteratively to satisfy the safety constraint. We pre-train a diffusion model on the training set. Given the calibration set and the specific control targets, we derive a provable safety bound using conformal prediction. After iteratively enhancing the safety of the diffusion model with the progressively updated bound, the model's output can be certified as safe with a user-defined probability. We evaluate our algorithm on two control tasks 1D Burgers' equation and 2D incompressible fluid. Our results show that our algorithm satisfies safety constraints, and outperforms prior control methods and safe offline RL algorithms.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: False

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: https://aclanthology.org/2023.acl-long.354/

url_pdf: 'https://openreview.net/forum?id=OkPDLLNLnM'
# url_code: 'https://github.com/Hytn/AspectSum'
# url_dataset: 'https://github.com/Hytn/DocRED-HWE'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://aclanthology.org/2023.acl-long.354.mp4'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
  # - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
# slides: example
---
