---
title: "MultiSafe: Multiple Flight Safety Events Prediction Based on Interpretable Deep Multi-Task Learning"
collection: publications
permalink: /publication/MultiSafe
#excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2025-04-19
venue: 'Submitted'
#slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
#paperurl: 'https://link.springer.com/article/10.1007/s00371-021-02174-7'
citation: 'Huang, Y., Shang, J., Li, X., et al. (2025). MultiSafe: Multiple Flight Safety Events Prediction Based on Interpretable Deep Multi-Task Learning.(Submitted)'
---

Flight safety remains a central concern in the civil aviation industry. Recently, increasing attention has been given to leveraging high-dimensional temporal flight data, typically collected by Quick Access Recorders (QAR), to predict safety events. However, most existing studies focus on individual safety events, overlooking the latent and often complex correlations among multiple events. For instance, during landing, a maneuver intended to reduce the risk of one event may inadvertently raise the risk of another. Predicting multiple events introduces three main challenges: (1) handling flight parameters recorded at inconsistent sampling rates, (2) learning task-specific parameter importance to enhance model interpretability, and (3) modeling complex temporal dependencies to improve prediction accuracy. To address these issues, we propose MultiSafe, a deep multi-task learning model for predicting and interpreting multiple flight safety events. First, to process parameters with heterogeneous frequencies, we introduce a Multi-Scale Shared Encoder using convolutional layers with adaptive kernel sizes to generate unified representations across tasks. Next, a Parameter Selector based on gating networks learns task-specific parameter importance, enabling interpretable predictions by identifying key operational features. Finally, a Temporal Decoder with a fine-grained attention mechanism captures intricate temporal dependencies among parameters. Experiments on a dataset of 37,518 A320 flight records show that MultiSafe outperforms state-of-the-art baselines in prediction accuracy. Moreover, its interpretability offers actionable insights to assist pilots in enhancing flight safety.
