---
title: "Debiasing Neighbor Aggregation for Graph Neural Network in Recommender Systems (CIKM 2022)"
authors:
- Minseok Kim
- Jinoh Oh
- Jaeyoung Do
- Sungjin Lee
date: "2022-10-17T00:00:00Z"
doi: "https://doi.org/10.1145/3511808.3557576"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-10-17T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Information and Knowledge Management*
publication_short: in *CIKM*

abstract: Graph neural networks (GNNs) have achieved remarkable success in recommender systems by representing users and items based on their historical interactions. However, little attention was paid to GNN's vulnerability to exposure bias: users are exposed to a limited number of items so that a system only learns a biased view of user preference to result in suboptimal recommendation quality. Although inverse propensity weighting is known to recognize and alleviate exposure bias, it usually works on the final objective with the model outputs, whereas GNN can also be biased during neighbor aggregation. In this paper, we propose a simple but effective approach, neighbor aggregation via inverse propensity (Navip) for GNNs. Specifically, given a user-item bipartite graph, we first derive propensity score of each user-item interaction in the graph. Then, inverse of the propensity score with Laplacian normalization is applied to debias neighbor aggregation from exposure bias. We validate the effectiveness of our approach through our extensive experiments on two public and Amazon Alexa datasets where the performance enhances up to 14.2%c:x.

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/2208.08847.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---

