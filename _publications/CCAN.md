---
title: "CCAN: Channel-wise Clustering and Attention Networks for Interpretable Hard Landing Prediction"
collection: publications
permalink: /publication/CCAN
#excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2025-06-20
venue: 'Submitted'
#slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
#paperurl: 'https://link.springer.com/article/10.1007/s00371-021-02174-7'
citation: 'Zhang, H., Sun, H., Liu, Y., Zhao, X., Li, X., Shang, J., Zheng, L.. (2025). CCAN: Channel-wise Clustering and Attention Networks for Interpretable Hard Landing Prediction.(Submitted)'
---

Hard landing incidents are common flight safety events during the landing phase and are of significant concern in the aviation industry. Recent hard landing prediction methods tend to overemphasize temporal features while overlooking the landing process along the altitude dimension. In addition, they often fail to capture the interdependencies between contributing factors, limiting their ability to provide interpretable predictions. To address the above issues, we propose a novel Channel Clustering based Attention Network, termed CCAN, to predict hard landing incidents and identify their potential causes. Specifically, we resample and interpolate different flight parameters along the altitude dimension to align the landing process across different flights into a common reference frame. Subsequently, we design a channel clustering module that groups flight parameters into distinct clusters based on a predefined assignment threshold. Then, we employ graph attention network to capture the dependencies between different flight parameters within and across clusters. To further reveal the interactions between flight parameters throughout the landing process, we incorporate attention mechanism into Gated Recurrent Units (GRUs) to extract informative temporal features. We conducted experiments on a real-world QAR dataset with 44,729 Airbus A321 flights. Experimental results demonstrate that CCAN outperforms the baseline models in hard landing predictions and offers interpretability for hard landings by visualizing the dependencies between flight parameters and their interactions during the landing process.
