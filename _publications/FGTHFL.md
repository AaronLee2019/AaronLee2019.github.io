---
title: "Fine-Grained Time and Hidden Feature Learning for Interpretable Hard Landing Prediction Based on QAR Data"
collection: publications
permalink: /publication/FGTHFL
#excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2025-05-26
venue: 'IEEE Transactions on Intelligent Transportation Systems'
#slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/11015832'
citation: 'Cai, J., Shang, J., Li, X., Li, C., & Zheng, L. (2025). Fine-Grained Time and Hidden Feature Learning for Interpretable Hard Landing Prediction Based on QAR Data. IEEE Transactions on Intelligent Transportation Systems.'
---

Hard landings, as a common type of aviation incident, have consistently attracted the attention of airlines and aviation authorities. In recent years, the widespread adoption of Quick Access Recorder (QAR) systems has led numerous researchers to focus on predicting hard landing events through the analysis of QAR data. However, most studies treat QAR data as standard time series without fully accounting for its unique characteristics. Unlike typical time series, QAR data exhibits limited periodicity and trends, making it challenging for traditional modeling approaches to capture its complex patterns. Furthermore, model interpretability, as an essential aspect for practical deployment and decision-making, remains insufficiently explored. To address these issues, we propose a Fine-Grained Time and Hidden Feature Learning model for Interpretable Hard Landing Prediction based on QAR Data (TF-QAR). Specifically, we introduce a novel fine-grained temporal aggregation module, which dynamically extracts the importance of each time step through learnable parameters, to efficiently model the temporal dependencies in QAR data. Additionally, we develop a feature aggregation module that introduces a learnable adjacency matrix to model the significance of flight features and their interrelationships, revealing not only key parameters that directly influence hard landings, but also hidden parameters that are indirectly related. We conducted extensive experiments using a dataset of 37,929 real A320 flight segments in China. The results demonstrate that our model outperforms existing state-of-the-art baselines. Moreover, by visualizing the learnable parameters, TF-QAR provides interpretable insights valuable for pilot decision-making, offering practical support for the prevention and management of hard landing events.
