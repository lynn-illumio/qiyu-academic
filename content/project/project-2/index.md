---
title: 'Active Learning in RL with Human Feedback'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
#authors:
#  - admin
#  - Pratik Ramprasad
#  - Zhengling Qi
#  - Will Wei Sun

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'

date: '2021-12-21T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
#publishDate: '2021-12-21T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
#publication: Journal of the American Statistical Association
#publication_short: In JASA

#abstract: In the line of research within tensor learning, I focus on off-policy evaluation through the introduction of a tensor MDP framework. This framework is particularly capable of capturing the dynamics of sequential decision-making processes when the state-action features are represented as tensors. Using tensor features in their original form as inputs—for instance, in neuro-imaging—preserves critical spatial information that could be diminished or lost when the data is simplistically converted into vector covariates for application in traditional modeling approaches. When the $Q$ function can be approximated using a tensor parameter with a low-rank structure, we develop a method for \textbf{estimating this low-rank tensor within the evolution of sequential decision-making processes}. Theoretical guarantees are established for our proposed estimation algorithm, laying the foundation for the pioneering integration of tensor methodologies into the RL setting.

# Summary. An optional shortened abstract.
summary: |
  - Develop frameworks to incorporate human feedback into reinforcement learning to refine reward struc-
  tures, ensuring agent behaviors align with domain-specific quality and safety standards.
  - Advance research on the critical role of human feedback in establishing action constraints for safety
  and fairness, aiming to improve RL algorithm adaptability in real-world applications.

tags: []

# Display this page in the Featured widget?
featured: true

show_date: false

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

In the realm of RL, the incorporation of human feedback serves as a framework for enhancing the agent's learning process through domain-specific insights. While conventional RL algorithms strive to maximize reward by interacting with their environment, defining what precisely constitutes a "reward" is often a complex task. Such definitions demand relevant domain knowledge to appropriately specify "good" and "bad" agent behaviors. Moreover, human feedback often plays a critical role in establishing action constraints to ensure safety and fairness. Research in this domain shows significant promise for enhancing the adaptability of RL algorithms across a wide range of real-world applications. However, there is still a lack of comprehensive scientific investigations in this area. As such, one of my forthcoming research objectives is to contribute substantively to the development of this field. 
