---
title: 'Off-Policy Evaluation For Low-Rank Tensor Markov Decision Processes.'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Pratik Ramprasad
  - admin
  - Zhengling Qi
  - Will Wei Sun

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'

date: ''
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
#publication: Journal of the American Statistical Association
#publication_short: In JASA

abstract: In the line of research within tensor learning, I focus on off-policy evaluation through the introduction of a tensor MDP framework. This framework is particularly capable of capturing the dynamics of sequential decision-making processes when the state-action features are represented as tensors. Using tensor features in their original form as inputs—for instance, in neuro-imaging—preserves critical spatial information that could be diminished or lost when the data is simplistically converted into vector covariates for application in traditional modeling approaches. When the Q function can be approximated using a tensor parameter with a low-rank structure, we develop a method for estimating this low-rank tensor within the evolution of sequential decision-making processes}. Theoretical guarantees are established for our proposed estimation algorithm, laying the foundation for the pioneering integration of tensor methodologies into the RL setting.

# Summary. An optional shortened abstract.
summary: |
  - **Collaboration**:
      - This is a collaborative work with Pratik Ramprasad, Zhengling Qi, and Will Wei Sun. To be submitted to JASA (Journal of the American Statistical Association), manuscript available upon request.

  - **Key Contributions**:
      - Developed a batch off-policy evaluation method to capture the low-rank structure in the tensor param- eter for the state-action value Q function.
      - Developed novel concentration inequalities for the suprema of certain matrix-valued empirical processes under Markovian noise.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

#url_pdf: 'https://arxiv.org/abs/2212.11385'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: 'An illustration of our matrix contextual bandit framework.'
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
---

