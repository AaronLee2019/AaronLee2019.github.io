---
title: "PathSAGE: Spatial Graph Attention Neural Networks with Random Path Sampling"
collection: publications
permalink: /publication/PathSAGE
#excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2021-12-07
venue: 'Neural Information Processing'
#slidesurl: 'https://doi.org/10.1007/978-3-030-92270-2_10'
paperurl: 'https://doi.org/10.1007/978-3-030-92270-2_10'
citation: 'Ma, J., Li, J., Li, X., & Li, X. (2021). PathSAGE: Spatial Graph Attention Neural Networks with Random Path Sampling. In Neural Information Processing: 28th International Conference, ICONIP 2021, Sanur, Bali, Indonesia, December 8–12, 2021, Proceedings, Part II 28 (pp. 111-120). Springer International Publishing.'
---

Graph Convolutional Networks (GCNs) achieve great success in non-Euclidean structure data processing recently. In existing studies, deeper layers are used in CCNs to extract deeper features of Euclidean structure data. However, for non-Euclidean structure data, too deep GCNs will confront with problems like “neighbor explosion” and “over-smoothing”, it also cannot be applied to large datasets. To address these problems, we propose a model called PathSAGE, which can learn high-order topological information and improve the model’s performance by expanding the receptive field. The model randomly samples paths starting from the central node and aggregates them by Transformer encoder. PathSAGE has only one layer of structure to aggregate nodes which avoid those problems above. The results of evaluation shows that our model achieves comparable performance with the state-of-the-art models in inductive learning tasks.
