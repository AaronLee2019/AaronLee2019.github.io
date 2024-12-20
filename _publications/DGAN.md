---
title: "DGAN: Flight sensor data anomaly detection based on dual-view graph attention network"
collection: publications
permalink: /publication/DGAN
#excerpt: 'This paper is about fixing template issue #693.'
date: 2024-10-20
venue: 'Submitted'
#paperurl: ''
citation: 'Yan, W., Li, X., Zheng, L., Shang, J., Wu, L., Lu, J., et al. (2024). DGAN: Flight sensor data anomaly detection based on dual-view graph attention network.'
---

A large amount of flight data is created by various sensors during flight, including pitch, roll, etc. These data often contain anomalies, reflecting potential factors that could lead to unsafe events. Thus, flight data anomaly detection is crucial for aviation safety, enabling the identification of deviations from normal operations. However, existing methods often fail to adequately extract temporal correlations and variable dependencies due to the complexity and high dimensionality of the flight data, resulting in inferior detection performance. This issue is particularly apparent when the anomaly data are scarce. To address these issues, we propose a novel anomaly detection model, named DGAN. Specifically, DGAN employs two parallel graph attention (GAT) layers to create embeddings that effectively capture the complex relationships among temporal correlations and variable dependencies. Additionally, it performs data augmentation on these embeddings to extract two views consistent with the underlying data patterns, thereby revealing broader data characteristics in the original spatial context. Based on these two views, DGAN constructs pairs of positive and negative samples and applies a dual-view contrastive method. This approach enables the model to capture local invariant features, ensuring effective anomaly detection even with scarce anomaly data. We conduct experiments on a dataset comprising 44,808 real-world flight samples from the Airbus A321 aircraft. The evaluation results suggest that the performance of DGAN exceeds state-of-the-art (SOTA) models. Moreover, we examine the effectiveness of DGAN through further visualizations and case studies.
