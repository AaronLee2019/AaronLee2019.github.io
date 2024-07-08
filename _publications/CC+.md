
---
title: "CurveCluster+: Curve Clustering for Hard Landing Pattern Recognition and Risk Evaluation Based on Flight Data"
collection: publications
permalink: /publication/CC+
#excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2021-10-13
venue: 'IEEE Transactions on Intelligent Transportation Systems'
paperurl: 'https://doi.org/10.1109/TITS.2021.3117846'
citation: 'Li, X., Shang, J., Zheng, L., Wang, Q., Sun, H., & Qi, L. (2021). Curvecluster+: Curve clustering for hard landing pattern recognition and risk evaluation based on flight data. IEEE Transactions on Intelligent Transportation Systems, 23(8), 12811-12821.'
---

Hard landing is a typical flight safety incident, and interpretability plays an important role in flight safety research. However, existing studies failed to provide good interpretability of the reasons for hard landing incidents and suffer from low prediction accuracy. To address the above problems, in this paper we propose CurveCluster+, a curve clustering method based on quick access recorder (QAR) data for hard landing risk evaluation. Specifically, we first conduct an in-depth analysis on hard landing flights by comparing key QAR parameter curves with the group behavior, based on which we establish a two-level hierarchical classification of hard landing incidents according to the hard landing patterns. Then we extract curve-level features from key QAR parameters through interpolation and resampling. After that we turn the classic K-means clustering into a semi-supervised algorithm by incorporating some expert experience and apply it on the curve-level features to automatically recognize the hard landing patterns. Finally, we propose a risk evaluation model based on the clustering results to discover high-risk flights from normal ones. We evaluate our method on a QAR dataset of 37,943 Airbus 320 aircraft flights. The results show that compared with other state-of-the-art data-driven methods, CurveCluster+ provides strong interpretability of hard landing incidents and exhibits good performance in recognizing hard landing patterns (the overall accuracy of our method reaches up to 92.99%). Moreover, it only requires a handful of hard landing samples to discover high-risk flights from tremendous normal landing flights, which is critical for flight safety warnings.
