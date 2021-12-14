---
title: "Task-Agnostic Undesirable Feature Deactivation Using Out-of-Distribution Data (NeurIPS 2021)"
authors:
- Dongmin Park
- Hwanjun Song
- Minseok Kim
- Jae-Gil Lee
date: "2021-10-05T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-10-05T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 35th Annual Conference on Neural Information Processing Systems"
publication_short: "NeurIPS"

abstract: A deep neural network (DNN) has achieved great success in many machine learning tasks by virtue of its high expressive power. However, its prediction can be easily biased to undesirable features, which are not essential for solving the target task and are even imperceptible to a human, thereby resulting in poor generalization. Leveraging plenty of undesirable features in out-of-distribution (OOD) examples has emerged as a potential solution for de-biasing such features, and a recent study shows that softmax-level calibration of OOD examples can successfully remove the contribution of undesirable features to the last fully-connected layer of a classifier. However, its applicability is confined to the classification task, and its impact on a DNN feature extractor is not properly investigated. In this paper, we propose TAUFE, a novel regularizer that deactivates many undesirable features using OOD examples in the feature extraction layer and thus removes the dependency on the task-specific softmax layer. To show the task-agnostic nature of TAUFE, we rigorously validate its performance on three tasks, classification, regression, and a mix of them, on CIFAR-10, CIFAR-100, ImageNet, CUB200, and CAR datasets. The results demonstrate that TAUFE consistently outperforms the state-of-the-art method as well as the baselines without regularization.


# links:
# - name: ""
#   url: ""
url_pdf: 'https://github.com/songhwanjun/songhwanjun.github.io/raw/master/files/2021_NeurIPS_TAUFE.pdf'
url_code: 'https://github.com/kaist-dmlab/TAUFE'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---

