---
title: "How Does Early Stopping Help Generalization against Label Noise? (ICMLW 2020)"
authors:
- Hwanjun Song
- Minseok Kim
- Dongmin Park
- Jae-Gil Lee
date: "2020-07-13T00:40:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-07-13T00:40:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Machine Learning, UDL Workshop*
publication_short: In *ICMLW*

abstract: Noisy labels are very common in real-world training data, which lead to poor generalization on test data because of overfitting to the noisy labels. In this paper, we claim that such overfitting can be avoided by “early stopping” training a deep neural network before the noisy labels are severely memorized. Then, we resume training the early stopped network using a “maximal safe set,” which maintains a collection of almost certainly true-labeled samples at each epoch since the early stop point. Putting them all together, our novel two-phase training method, called Prestopping, realizes noise-free training under any type of label noise for practical use. Extensive experiments using four image benchmark data sets verify that our method significantly outperforms four state-of-the-art methods in test error by 0.4–8.2 percent points under existence of real-world noise.

# links:
# - name: ""
#   url: ""
url_pdf: 'http://www.gatsby.ucl.ac.uk/~balaji/udl2020/accepted-papers/UDL2020-paper-020.pdf'
url_code: 'https://bit.ly/2l3g9Jx'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---

