---
title: "IMTCN: An Interpretable Flight Safety Analysis and Prediction Model Based on Multi-Scale Temporal Convolutional Networks"
collection: publications
permalink: /publication/IMTCN
#excerpt: 'This paper is about fixing template issue #693.'
date: 2023-09-14
venue: 'IEEE Transactions on Intelligent Transportation Systems'
paperurl: 'https://doi.org/10.1109/TITS.2023.3308988'
citation: 'Li, X., Shang, J., Zheng, L., Wang, Q., Liu, D., Liu, X., ... & Sun, H. (2023). IMTCN: An Interpretable Flight Safety Analysis and Prediction Model Based on Multi-Scale Temporal Convolutional Networks. IEEE Transactions on Intelligent Transportation Systems.'
---

Flight safety is a key issue in the aviation industry. Recently, with the prevalence of flight data recording systems, some deep learning-based studies have been devoted to predicting safety incidents based on flight data. However, these studies, although they exhibit higher prediction accuracy, have largely neglected the interpretability analysis of safety incidents which is of great concern to airlines and pilots. To address this issue, we define flight safety prediction as a multiscale time series classification problem and propose an interpretable model named IMTCN to provide both accurate predictions and high interpretability of flight safety. First, multiple temporal convolutional networks (TCNs) are utilized to capture local representations and long effective histories from multivariate flight data. Because different flight parameters are collected with diverse sampling frequencies, multiple TCNs are used to handle these parameters separately. Then, we creatively adapt the class activation mapping (CAM) method, which has been used for interpretation in image classification, and combine it with the TCN to provide flight data interpretability. The established model can pinpoint key flight parameters and corresponding moments that contribute most to safety incidents. Experimental results on a real-world dataset with 37,943 Airbus A320 aircraft flights show that our model outperforms the baselines on the task of exceedance classification and prediction 2 seconds and 4 seconds in advance, and case studies demonstrate its superb interpretability for flight safety analysis.
