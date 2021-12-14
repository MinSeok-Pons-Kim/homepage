---
title: "Robust Learning by Self-Transition for Handling Noisy Labels (KDD 2021)"
authors:
- Hwanjun Song
- Minseok Kim
- Dongmin Park
- Yooju Shin
- Jae-Gil Lee
date: "2021-05-17T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-05-17T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 27th ACM SIGKDD International Conference on Knowledge Discovery and Data Mining"
publication_short: "KDD"

abstract: Real-world data inevitably contains noisy labels, which induce the poor generalization of deep neural networks. It is known that the network typically begins to rapidly memorize false-labeled samples after a certain point of training. Thus, to counter the label noise challenge, we propose a novel self-transitional learning method called MORPH, which automatically switches its learning phase at the transition point from seeding to evolution. In the seeding phase, the network is updated using all the samples to collect a seed of clean samples. Then, in the evolution phase, the network is updated using only the set of arguably clean samples, which precisely keeps expanding by the updated network. Thus, MORPH effectively avoids the overfitting to false-labeled samples throughout the entire training period. Extensive experiments using five real-world or synthetic benchmark datasets demonstrate substantial improvements over state-of-the-art methods in terms of robustness and efficiency.

# links:
# - name: ""
#   url: ""
url_pdf: 'https://github.com/songhwanjun/songhwanjun.github.io/raw/master/files/2021_KDD__MORPH.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---

