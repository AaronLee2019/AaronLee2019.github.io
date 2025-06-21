---
title: "DGAN: Flight sensor data anomaly detection based on dual-view graph attention network"
collection: publications
permalink: /publication/DGAN
#excerpt: 'This paper is about fixing template issue #693.'
date: 2025-04-28
venue: 'IEEE Sensors Journal'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10979258/'
citation: 'Yan, W., Li, X., Zheng, L., Shang, J., Wu, L., Liu, H., ... & Qian, Y. (2025). DGAN: Flight data anomaly detection based on dual-view graph attention network. IEEE Sensors Journal.'
---

A large number of flight data is collected by various sensors during flight, including altitude, speed, pitch, etc. Flight unsafe events, such as hard landings, can be reflected in flight anomaly data. Thus, flight data anomaly detection is crucial for aviation safety, enabling the identification of deviations from normal operations. However, due to the complexity and high dimensionality of the flight data, existing methods often fail to adequately extract temporal and variable information. As a result, these methods exhibit poor detection performance, especially when the anomaly data is scarce. To address these issues, we propose a novel Dual-view Graph Attention Network (DGAN) model for flight data anomaly detection. Specifically, two parallel Graph Attention (GAT) layers are employed to create embeddings that are rich in temporal correlations and variable dependencies. And TCN-based autoencoder module is proposed for data augmentation on these embeddings to extract two views consistent with the underlying data patterns. Furthermore, DGAN constructs pairs of positive and negative samples both within a single view and between different views. A dual-view contrastive training strategy is proposed to construct contrastive loss, which can learn a good representation of flight sequence and ensure effective anomaly detection even in cases of scarce anomaly data. We conduct experiments on a dataset comprising 44,808 real-world flight samples from the Airbus A321. The results demonstrate that the performance of DGAN exceeds state-of-the-art (SOTA) models. Moreover, we examine the effectiveness of DGAN through further visualizations and case studies.
