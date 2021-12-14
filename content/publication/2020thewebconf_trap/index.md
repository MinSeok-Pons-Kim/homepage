---
title: "TRAP: Two-level Regularized Autoencoder-based Embedding for Power-law Distributed Data (TheWebConf 2020)"
authors:
- Dongmin Park
- Hwanjun Song
- Minseok Kim
- Jae-Gil Lee
date: "2020-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *The Web Conference*
publication_short: In *TheWebConf*

abstract: Finding low-dimensional embeddings of sparse high-dimensional data objects is important in many applications such as recommendation, graph mining, and natural language processing (NLP). Recently, autoencoder (AE)-based embedding approaches have achieved state-of-the-art performance in many tasks, especially in top-k recommendation tasks with user embedding or node classification tasks with node embedding. However, we find that many real-world data follow the power-law distribution with respect to the data object sparsity. When learning AE-based embeddings of these data, dense inputs move away from sparse inputs in an embedding space even when they are highly correlated. Resultingly, the embedding is distorted, which we call the polarization problem. In this paper, we propose TRAP that leverages two-level regularizers to effectively alleviate this problem. (i) The macroscopic regularizer adds a regularization term in the loss function to generally prevent dense input objects from being distant from other sparse input objects. (ii) The microscopic regularizer introduces a new object-wise parameter to individually entice each object to correlated neighbor objects rather than uncorrelated ones. Importantly, TRAP is a meta-algorithm that can be easily coupled with existing AE-based embedding methods with a simple modification. In extensive experiments on two representative embedding tasks using six-real world datasets, TRAP boosted the performance of the state-of-the-art algorithms by up to 31.53% and 94.99% respectively.

# links:
# - name: ""
#   url: ""
url_pdf: 'http://dm.kaist.ac.kr/lab/papers/webconf20.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---

