---
title: "WTAN: Wavelet Transform-based Attention Network for Tail Strike Prediction and Interpretable Analysis"
collection: publications
permalink: /publication/WTAN
#excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2025-06-20
venue: 'Submitted'
#slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
#paperurl: 'https://link.springer.com/article/10.1007/s00371-021-02174-7'
citation: 'Xiong, D., Li, X., Song, E., et al. (2025). WTAN: Wavelet Transform-based Attention Network for Tail Strike Prediction and Interpretable Analysis.(Submitted)'
---

Tail strike incidents are common flight safety events that typically occur during the landing phase. With the widespread deployment of Quick Access Recorders (QAR), large volumes of high-dimensional and heterogeneous flight data have become available. However, existing studies on flight safety often struggle to effectively capture multi-scale frequency temporal patterns and complex interrelationships among various flight parameters, resulting in suboptimal performance in tail strike prediction. To address the above issues, we propose a Wavelet Transform-based Attention Network, termed WTAN, to predict and interpret tail strike incidents, thereby enhancing flight safety. Specifically, we utilize Temporal Convolutional Networks (TCN) and Gated Recurrent Units (GRU) to standardize flight parameters with varying sampling frequencies to a unified sample length. To further enrich temporal frequency feature representation, we integrate wavelet transform with a multi-head attention mechanism, allowing the model to jointly exploit both temporal and frequency-domain information for more comprehensive pattern recognition. Additionally, we employ graph attention network to model the complex interrelationships between different flight parameters. We validate the effectiveness of WTAN on a real-world QAR dataset consisting of 44,808 Airbus A321 flight records. Experimental results demonstrate that WTAN significantly outperforms the baseline models in predictive accuracy and offers interpretable insights into the causes of flights with high tail strike risk by visualizing the contributions of different flight parameters.
