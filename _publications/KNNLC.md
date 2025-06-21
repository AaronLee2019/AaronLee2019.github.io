---
title: "Boosting Low-budget Active Learning with Label Calibration and Unsupervised Representations"
collection: publications
permalink: /publication/KNNLC
#excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2025-02-03
venue: 'Submitted'
#slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
#paperurl: 'https://link.springer.com/article/10.1007/s00371-021-02174-7'
citation: 'Han, Y., Shang, J., Li, R., Li, X., Liao, L., Zheng, L., & Min, G.. (2025). Boosting Low-budget Active Learning with Label Calibration and Unsupervised Representations. IEEE Transactions on Pattern Analysis and Machine Intelligence. (Submitted)'
---

In active learning research, low-budget active learning poses a significant challenge, primarily due to the scarcity of labeled examples available for training the target model. This limitation often leads to the model’s tendency to make approximately stochastic predictions for examples with confusing category features, a phenomenon known as catastrophic forgetting. To address this challenge, this paper proposes a novel and unified framework that leverages label calibration and unsupervised representations, aiming to boost the performance of active learning algorithms in low-budget scenarios. Specifically, to cope with the scarcity of labeled data, we perform pre-training on the entire unlabeled dataset to generate unsupervised representations that are rich in geometric information. These representations are then used by diversity-based active learning algorithms to query examples for labeling. To address model instability, we creatively calibrate pseudo-labels of unlabeled examples using statistical information derived from model outputs during training. These calibrated pseudo-labels, combined with the unsupervised representations, are then fed into a KNN classification model to generate predictions for test examples. Theoretical analysis reveals that our approach exhibits a tighter bound on generalization error, and empirical results demonstrate its superior effectiveness in boosting the performance of active learning algorithms under low-budget constraints.
