---
title: "MGAN: Multi-scale Graph Attention Network for Flight Safety Incidents Detection"
collection: publications
permalink: /publication/MGAN
#excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2025-04-30
venue: 'Submitted'
#slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
#paperurl: 'https://link.springer.com/article/10.1007/s00371-021-02174-7'
citation: 'Yan, W., Li, X., Zhao, X., et al. (2025). MGAN: Multi-scale Graph Attention Network for Flight Safety Incidents Detection.(Submitted)'
---

The approach and landing phases are the stages with the highest frequency of safety incidents during the flight of a civil aviation aircraft. The factors influencing these incidents are often reflected in flight data, making the analysis of such data crucial for detecting incidents. The Quick Access Recorder (QAR), an essential onboard device in commercial aircraft, collects vast amounts of flight data generated by various Internet of Things (IoT) devices. The integration of QAR data with artificial intelligence technologies has made significant progress in the field of aviation safety analysis. However, existing detection approaches frequently struggle to accurately model the dependencies and interactions among flight variables, which exhibit high dimensionality and varying temporal frequencies, thereby undermining detection accuracy. Moreover, numerous approaches depend on opaque black-box models, which offer limited interpretability. To address these challenges, we introduce the Multi-scale Graph Attention Network (MGAN), a novel anomaly detection framework that integrates multivariate flight data sampled at varying frequencies to identify events and provide interpretable insights into their causes. MGAN proposes a Hybrid Temporal Network (HTN), which combines Gated Recurrent Units (GRU) with Dilated Causal Convolutions to capture long-range dependencies and complex interactions among flight variables. Additionally, the Cross-frequency Graph Attention Network (GAT) models dependencies across different sampling frequencies, enabling the extraction of multi-level feature representations. Extensive experiments on the QAR dataset of 44,808 Airbus A321 flights operated by Chinese airlines demonstrate that MGAN significantly outperforms state-of-the-art models in anomaly detection tasks, while also providing interpretative analyses of the underlying causes of safety incidents.
