---
title: "Crossperformer: Cross-period Transformer for Time Series Forecasting"
collection: publications
permalink: /publication/Crossperformer
#excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2025-05-16
venue: 'Submitted'
#slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
#paperurl: 'https://link.springer.com/article/10.1007/s00371-021-02174-7'
citation: '* (2025). Crossperformer: Cross-period Transformer for Time Series Forecasting. (Submitted)'
---

Time series data often exhibit multiple periodic characteristics that are critical for accurate forecasting and understanding system dynamics. Recently, the effectiveness of existing Transformer-based time series forecasting methods has been challenged, these methods typically embed multiple variables at the same timestamp using Transformers, relying on self-attention mechanisms to predict future horizons based solely on correlations between embedded tokens. However, this approach results in attention maps that fail to capture the periodic nature of time series data effectively. To address this limitation, we propose cross-period Transformer (Crossperformer), an enhanced model designed specifically for multi-period time series data. We introduce a periodic segment embedding method and develop a cross-period attention mechanism, enabling Crossperformer to explicitly capture periodic patterns and effectively model cross-period dependencies among variables. To further advance temporal representation learning, we employ a feed-forward network with periodic activation functions to learn generalized periodic patterns, thereby enhancing both prediction accuracy and generalization capabilities of the framework. Experimental results on multiple real-world benchmark datasets demonstrate that Crossperformer achieves state-of-the-art performance in long-term time series forecasting tasks. Our findings indicate that Transformers are inherently unsuitable for time series forecasting, since they cannot handle the periodicity in time series data. This research opens new avenues for future exploration in this domain.
