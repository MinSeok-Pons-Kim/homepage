---
title: "Meta-Learning for Online Update of Recommender Systems (AAAI 2022)"
authors:
- Minseok Kim
- Hwanjun Song
- Yooju Shin
- Dongmin Park
- Kijung Shin
- Jae-Gil Lee
date: "2021-12-06T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-12-06T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 35th Annual Conference on Neural Information Processing Systems"
publication_short: "The AAAI Conference on Artificial Intelligence"

abstract: Online recommender systems should be always aligned with users' current interest to accurately suggest items that each user would like. Since user interest usually evolves over time, the update strategy should be flexible to quickly catch users' current interest from continuously generated new user-item interactions. Existing update strategies focus either on the importance of each user-item interaction or the learning rate for each recommender parameter, but such one-directional flexibility is insufficient to adapt to varying relationships between interactions and parameters. In this paper, we propose MeLON, a meta-learning based novel online recommender update strategy that supports two-directional flexibility. It is featured with an adaptive learning rate for each parameter-interaction pair for inducing a recommender to quickly learn users' up-to-date interest. The procedure of MeLON is optimized following a meta-learning approach; it learns how a recommender learns to generate the optimal learning rates for future updates. Specifically, MeLON first enriches the meaning of each interaction based on previous interactions and identifies the role of each parameter for the interaction; and then combines these two pieces of information to generate an adaptive learning rate. Theoretical analysis and extensive evaluation on three real-world online recommender datasets validate the effectiveness of MeLON.


# links:
# - name: ""
#   url: ""
url_pdf: ""
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---

