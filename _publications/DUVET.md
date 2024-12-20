---
title: "DUVET: Dual View Enhanced Transformer for Multivariate Flight Time series Anomaly Detection"
collection: publications
permalink: /publication/DUVET
#excerpt: 'This paper is about fixing template issue #693.'
date: 2024-12-11
venue: 'Submitted'
#paperurl: ''
citation: 'Li, C., Li, X., Chen, H., Zheng, L., Sun, H., Shang, J. (2024). DUVET: Dual View Enhanced Transformer for MultivariateFlight Time series Anomaly Detection.'
---

In recent years, the prevalence of modern flight data recording systems such as Quick Access Recorder (QAR), has made it viable to improve flight safety by analyzing large volumes of flight parameters. However, existing studies mostly concentrate on specific safety events and heavily depend on expert-labeled data where the labels are highly scarce and imbalanced. To fully utilize valuable information from the tremendous unlabeled data, in this paper we focus on uncovering abnormal flight patterns and define it as an self-supervised time series anomaly detection problem, enabling us to discover potential and unexpected safety risks. To this end, we propose DUVET, a reconstructionbased Dual View Enhanced Transformer model for multivariate flight time series anomaly detection. Specifically, DUVET adopts Patching and Channel Independence techniques to reduce model parameters and improve Transformer’s computational efficiency of attention mechanism while preserving its semantic representation capacity. Based on the observation that flight safety usually relates to both long-term patterns and short-term deviations, we pioneer a new Bell Attention mechanism, and combine it with Transformer’s self-attention, to capture local and global dependencies respectively, which largely enhances the model reconstruction ability. We first evaluate DUVET on six public real-world datasets and one QAR dataset, demonstrating that DUVET achieves state-of-the-art performance in general time series anomaly detection task, and the ablation study clearly shows the vital role of Bell Attention. Further experiments on the QAR dataset show that DUVET meets key criteria of anomaly detection for flight safety in terms of stability, training efficiency and detection accuracy. Case study shows that DUVET can effectively uncover hidden flight safety risks.
