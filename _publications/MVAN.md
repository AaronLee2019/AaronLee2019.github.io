---
title: "MVAN: Towards Interpretable Joint Prediction of Multiple Flight Safety Events with Multi-View Attention Network"
collection: publications
permalink: /publication/MVAN
#excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2025-05-15
venue: 'Submitted'
#slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
#paperurl: 'https://link.springer.com/article/10.1007/s00371-021-02174-7'
citation: 'Li, C., Li, X., Zheng, L., Shang, J., et al. (2025). MVAN: Towards Interpretable Joint Prediction of Multiple Flight Safety Events with Multi-View Attention Network.(Submitted)'
---

Recently, the use of multivariate flight data for safety event analysis has attracted significant attention from both academia and industry. However, most existing studies focus on individual safety events, overlooking the joint prediction and interpretation of multiple interrelated events, which hinders effective risk management given the inherent coupling among such events. Moreover, the complex nature of flight data, characterized by multi-scale temporal dynamics and intricate inter-parameter correlations, poses substantial analytical challenges. To address these issues, we propose MVAN, a novel Multi-View Attention Network that jointly predicts and interprets multiple flight safety events by modeling the flight data from temporal, parametric, and event-specific perspectives. MVAN introduces two specialized attention mechanisms: Time Trend Attention, which captures temporal patterns and abrupt changes through various convolutional operations, and Gaussian-Enhanced Attention, which models both global and local inter-parameter dependencies via a hybrid approach. Furthermore, we design a Multi-Task Variable Selection Module to dynamically identify shared and task-specific features, thereby enhancing interpretability. Extensive experiments on a real-world flight dataset demonstrate that MVAN not only outperforms baseline models in predicting hard landing and tail strike events, but also effectively uncovers the coupling relationships between these events. In-depth case studies further validate the interpretability of the model by revealing both shared and event-specific parameter dependencies, offering actionable insights for flight operations and risk mitigating strategies.
