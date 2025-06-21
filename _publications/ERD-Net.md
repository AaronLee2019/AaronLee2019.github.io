---
title: "ERD-Net: Modeling entity and relation dynamics for Temporal Knowledge Graph reasoning"
collection: publications
permalink: /publication/ERD-Net
#excerpt: 'This paper is about fixing template issue #693.'
date: 2025-03-28
venue: 'Knowledge-Based Systems'
paperurl: 'https://doi.org/10.1016/j.engappai.2025.110911'
citation: 'Liao, L., Zheng, L., Chen, F., Shang, J., Li, X., & Li, W. (2025). ERD-Net: Modeling entity and relation dynamics for Temporal Knowledge Graph reasoning. Knowledge-Based Systems, 317, 113404.'
---

Temporal Knowledge Graph (TKG) has garnered significant attention and applications due to its immense potential and impact in event prediction. Existing approaches primarily focus on learning low-dimensional embeddings of entities and relations to predict valid triples. Despite notable advancements, these methods face challenges such as inadequate modeling of relation dynamics and limited exploration of non-repeated patterns. To address these issues, we propose the Entity and Relation Dynamic representation learning Network (ERD-Net), a novel framework that combines dynamic representation learning with a copy-generation mechanism to enhance TKG reasoning. ERD-Net begins by learning intrinsic embeddings for entities and relations, capturing their time-invariant properties. These embeddings are subsequently frozen during the dynamic learning phase to ensure stability. In the dynamic representation learning stage, we extend beyond entity dynamics to explore relation dynamics, distinguishing between global and local categories to evaluate their distinct contributions. Furthermore, a copy-generation mechanism is introduced in the decoder, enabling simultaneous modeling of both historical repeated patterns and novel non-repeated patterns. Comprehensive experiments on public benchmarks validate the efficacy of our approach. The results demonstrate that ERD-Net achieves state-of-the-art performance in TKG reasoning by effectively integrating dynamic representation learning with copy-generation mechanisms. Notably, our findings reveal that improving the prediction of non-repeated patterns can significantly enhance performance, highlighting a promising direction for future research in TKG reasoning.
