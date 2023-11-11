---
title: 'Statistical Inference for Contextual Bandit with Delayed Action Effects'

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

#date: '2021-12-21T00:00:00Z'
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

# Summary. An optional shortened abstract.
summary: |
  - Investigate the delayed effects of actions in critical settings, such as healthcare, where the impact of
  medications emerges over time and is linked to past decisions.
  - Conduct statistical inference on delayed feedback in contextual bandit frameworks, aiming to rigorously
  evaluate drug effects and optimize decision-making in healthcare applications.

abstract:
  In many real-world situations, the consequences of actions are not immediately apparent and may only become observable after a certain time has elapsed. For instance, in healthcare settings where medications are administered to patients, the drug's effects are not instantly evident. Often, the current reward or outcome is connected to past actions. Although some existing literature has addressed this temporal aspect by considering time-discounted effects or delayed consequences, the role of statistical inference becomes crucial when it comes to sensitive applications like medication administration. Extra caution is required before making any recommendations regarding drug intake, highlighting the need for rigorous statistical evaluation. The application-driven motivation for this line of research can be rooted in the study of medication effects for diabetes, where the historical medical treatment has prolonged effects on the current patients' well-being. A significant challenge in this context is the violation of the Markov assumption, due to the extended impact of treatment actions. Within the scope of this study, my objective is to develop a methodology that transforms conventional problem settings, predominantly centered around off-policy evaluation, into Markov Decision Processes. This transformation will facilitate the application of established RL algorithms to this domain.


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
In many real-world situations, the consequences of actions are not immediately apparent and may only become observable after a certain time has elapsed. For instance, in healthcare settings where medications are administered to patients, the drug's effects are not instantly evident. Often, the current reward or outcome is connected to past actions. Although some existing literature has addressed this temporal aspect by considering time-discounted effects or delayed consequences, the role of statistical inference becomes crucial when it comes to sensitive applications like medication administration. Extra caution is required before making any recommendations regarding drug intake, highlighting the need for rigorous statistical evaluation. The application-driven motivation for this line of research can be rooted in the study of medication effects for diabetes, where the historical medical treatment has prolonged effects on the current patients' well-being. A significant challenge in this context is the violation of the Markov assumption, due to the extended impact of treatment actions. Within the scope of this study, my objective is to develop a methodology that transforms conventional problem settings, predominantly centered around off-policy evaluation, into Markov Decision Processes. This transformation will facilitate the application of established RL algorithms to this domain.

