---
title: "MDGNN: Multiple Flight Safety Incidents Prediction Model Based on Dynamic Graph Neural Networks"
collection: publications
permalink: /publication/MDGNN
#excerpt: 'This paper is about fixing template issue #693.'
date: 2024-10-01
venue: 'Submitted'
#paperurl: ''
citation: 'Song, L., Li, X., Liu, H., Wu, L., Sun, H., Zheng, L., Shang, J.(2024). MDGNN: Multiple Flight Safety Incidents Prediction Model Based on Dynamic Graph Neural Networks.'
---

Flight safety incidents, such as hard landings and tail strike risks, represent critical concerns during the landing phase. Although Quick Access Recorder (QAR) systems collect extensive multivariate flight data, previous studies have faced challenges in effectively modeling the complex interdependencies between flight parameters, which has limited their ability to predict multiple safety incidents simultaneously. To address this issue, we propose a novel model, named MDGNN, to capture hidden spatio-temporal dependencies and predict both hard landing and tail strike risk incidents. Specifically, we employ temporal convolutional networks (TCNs) to extract both localized representations and long-term temporal trends from multivariate flight data, ensuring the standardization of flight parameters across varying frequencies. Additionally, we are the first to construct a dynamic graph to model temporal relationships, applying a dynamic graph neural network and a temporal convolution module to accurately capture intricate spatial and temporal dependencies. Extensive experiments conducted on 37,904 Airbus A320 flight samples demonstrate that the MDGNN model surpasses state-of-the-art baselines with high prediction accuracy. Furthermore, a case study visualizing key flight parameters highlights the model’s ability to reveal the root causes of safety exceedances, offering valuable insights for flight safety analysis.
