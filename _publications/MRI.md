---
title: "MRI: Memory Retention Mechanism for Interpretable Time Series Forecasting"
collection: publications
permalink: /publication/MRI
#excerpt: 'This paper is about fixing template issue #693.'
date: 2025-03-07
venue: 'Submitted'
#paperurl: ''
citation: 'Li, X., Zheng, L., Shang, J., Liao, L., Zhang, J., & Zhong, J. (2025). MRI: Memory Retention Mechanism for Interpretable Time Series Forecasting. IEEE Transactions on Pattern Analysis and Machine Intelligence.(Submitted)'
---

Interpretability in time series forecasting is crucial for building reliable models in mission-critical applications. While most studies prioritize improving prediction accuracy through complex model designs, few explore how models derive predictions from data patterns, limiting the understanding of model behavior across diverse datasets. Addressing this gap requires solving two key challenges: enhancing interpretability by retaining critical information and maintaining non-linearity for high forecasting performance. To this end, we propose MRI, a Memory Retention mechanism for Interpretable time series forecasting. Inspired by human brain’s forgetting mechanism, we design a novel memory retention module to discard irrelevant information and a memory recall module to retain sparse but important data, which largely improve model interpretability. To preserve non-linearity, we introduce learnable nonlinear functions with theoretical convergence guarantees, eliminating the need for manual selection of activation function. The combination of linear weights and learnable nonlinear functions, with well-defined relevance importance, enables both model-level and instance-level interpretations. Extensive experiments on nine real-world datasets demonstrate that MRI achieves state-of-the-art performance with competitive computational efficiency. Additionally, MRI demonstrates strong robustness against Gaussian noise and effectively captures periodic and trend patterns, providing meaningful model-level and instance-level explanations. The nature-inspired approach offers a new paradigm for building interpretable and robust deep learning models.
