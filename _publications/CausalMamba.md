---
title: "Causal Mamba for Multivariate Time Series Forecasting"
collection: publications
permalink: /publication/CausalMamba
#excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2025-05-16
venue: 'Submitted'
#slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
#paperurl: 'https://link.springer.com/article/10.1007/s00371-021-02174-7'
citation: '* (2025). Causal Mamba for Multivariate Time Series Forecasting. (Submitted)'
---

Multivariate time-series forecasting (MTSF) is essential for decision-making in various domains. As modern systems grow in complexity, effectively modeling inter-variable dependency has become increasingly important. Mamba, a recent state space model known for its ability to capture long-range dependencies, has also been adapted to model correlations among variables. However, vanilla-Mamba ignores causal direction/sequential order between variables, which limits their effectiveness in discovering complex dependency patterns. To address this, we propose Causal Mamba, a novel Mamba model for MTSF tasks. Specifically, we incorporate a Granger causality and topological sorting method to extract the causal order of variables. Subsequently, we employ the causal order information to modify vanilla-Mamba into Dynamic Mamba, which captures directional inter-variable dependency. Then we use TCN and FFN to model temporal dependency. Comprehensive experiments conducted on six real-world datasets demonstrate the efficacy of our model in improving forecasting performance, and validate the effectiveness of causal order of variables compared to vanilla-Mamba.
