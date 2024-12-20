---
title: "ATPF: An Adaptive Temporal Perturbation Framework for Adversarial Attacks on Temporal Knowledge Graph"
collection: publications
permalink: /publication/ATPF
#excerpt: 'This paper is about fixing template issue #693.'
date: 2024-12-04
venue: 'IEEE Transactions on Knowledge and Data Engineering'
paperurl: 'https://10.1109/TKDE.2024.3510689'
citation: 'Liao, L., Zheng, L., Shang, J., Li, X., & Chen, F. (2024). ATPF: An Adaptive Temporal Perturbation Framework for Adversarial Attacks on Temporal Knowledge Graph. IEEE Transactions on Knowledge and Data Engineering.'
---

Robustness is paramount for ensuring the reliability of knowledge graph models in safety-sensitive applications. While recent research has delved into adversarial attacks on static knowledge graph models, the exploration of more practical temporal knowledge graphs has been largely overlooked. To fill this gap, we present the Adaptive Temporal Perturbation Framework (ATPF), a novel adversarial attack framework aimed at probing the robustness of temporal knowledge graph (TKG) models. The general idea of ATPF is to inject perturbations into the victim model input to undermine the prediction. Firstly, we propose the Temporal Perturbation Prioritization (TPP) algorithm, which identifies the optimal time sequence for perturbation injection before initiating attacks. Subsequently, we design the Rank-Based Edge Manipulation (RBEM) algorithm, enabling the generation of both edge addition and removal perturbations under black-box setting. With ATPF, we present two adversarial attack methods: the stringent ATPF-hard and the more lenient ATPF-soft, each imposing different perturbation constraints. Our experimental evaluations on the link prediction task for TKGs demonstrate the superior attack performance of our methods compared to baseline methods. Furthermore, we find that strategically placing a single perturbation often suffices to successfully compromise a target link.
