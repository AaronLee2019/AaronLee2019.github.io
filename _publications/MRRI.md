---
title: "MRRI: Memory Retention Mechanism for Robust and Interpretable Time Series Forecasting"
collection: publications
permalink: /publication/MRRI
#excerpt: 'This paper is about fixing template issue #693.'
date: 2024-12-20
venue: 'Submitted'
#paperurl: ''
citation: 'Li, X., Zheng, L., Shang, J., Liao, L., & Zhang, J. (2024). MRRI: Memory Retention Mechanism for Robust and Interpretable Time Series Forecasting.'
---

Time series forecasting, due to its wide range of applications, has been a hot research topic in recent decades. However, existing studies are mostly dedicated to orchestrating more accurate or efficient deep learning models, while no study has yet focused on exploring the model's internal mechanism. To address this open issue and inspired by the forgetting mechanism of human brain, in this paper we propose Memory Retention mechanism for Robust and Interpretable time series forecasting, denoted as \textbf{MRRI}. Specifically, we incorporate the forgetting curve function into our designed memory retention mechanism, enabling the model to forget information in an exponential form to explain how itself works. Through this mechanism, MRRI can facilitate the elimination of irrelevant information and enhance the model robustness against noise. Subsequently, we design a memory recall module to retrieve and identify important memories/information for the model interpretability. To further enhance its nonlinear expressiveness, we employ learnable nonlinear activations to learn the nonlinearity of time series data and give theoretical analysis to prove its convergence. Experimental results on nine real-world datasets demonstrate that MRRI achieves state-of-the-art (SOTA) performance, and it degrades less than compared baselines after noise injection, exhibiting substantial robustness. The nature-inspired forgetting mechanism provides a promising idea for building highly interpretable and robust deep learning models.
