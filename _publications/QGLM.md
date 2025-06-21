---
title: "Query-Guided Temporal Confidence Network for Noisy Temporal Knowledge Graph Reasoning"
collection: publications
permalink: /publication/QGLM
#excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2025-06-20
venue: 'Submitted'
#slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
#paperurl: 'https://link.springer.com/article/10.1007/s00371-021-02174-7'
citation: 'Liao, L., Zheng, L., Shang, J., Li, X., Zhong, J., & Wei, K.. (2025). Query-Guided Temporal Confidence Network for Noisy Temporal Knowledge Graph Reasoning.'
---

The presence of noise in real-world Temporal Knowledge Graphs (TKGs) severely hampers the performance of reasoning models. While prior research primarily addresses input noise—erroneous or irrelevant historical facts—by refining temporal aggregation, it largely overlooks the detrimental impact of label noise, where inaccurate future facts are used as training supervision. Furthermore, most existing methods treat all historical information equally, ignoring its varying relevance to the specific query, which weakens their ability to effectively filter noise. To address these issues, we propose QGTC-Net, a Query-Guided Temporal Confidence Network that robustly performs TKG reasoning under both input and label noise. QGTC-Net introduces two novel components: (1) a Query-Guided Learning Mechanism (QGLM) that dynamically extracts query-relevant information from historical snapshots via a dual-path architecture, enhancing targeted and query-sensitive history modeling; and (2) a Confidence-Aware Optimization Mechanism(CAOM) that evaluates the reliability of training labels by jointly assessing their temporal alignment and local structural plausibility, allowing the model to selectively optimize on high-confidence facts. Extensive experiments on four widely-used TKG benchmarks and their noisy counterparts demonstrate that QGTC-Net consistently outperforms state-of-the-art baselines across both clean and noisy settings, underscoring its effectiveness and robustness in real-world scenarios. 
