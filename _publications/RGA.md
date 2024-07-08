---
title: "A Relation-Guided Attention Mechanism for Relational Triple Extraction"
collection: publications
permalink: /publication/RGA
#excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2021-09-20
venue: '2021 International Joint Conference on Neural Networks (IJCNN)'
#slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://doi.org/10.1109/ijcnn52387.2021.9533950'
citation: 'Yang, Y., Li, X., & Li, X. (2021, July). A relation-guided attention mechanism for relational triple extraction. In 2021 International Joint Conference on Neural Networks (IJCNN) (pp. 1-8). IEEE.'
---

Relational triples are the essential parts of knowledge graphs, which can be usually found in natural language sentences. Relational triple extraction aims to extract all entity pairs with semantic relations from sentences. Recent studies on triple extraction focus on the triple overlap problem where multiple relational triples share single entities or entity pairs in a sentence. Besides, we find sentences may contain implicit relations, and it is challenging for most existing methods to extract implicit relational triples whose relations are implicit in the sentence. In this paper, we propose a relation-guided attention mechanism (RGAM) for relational triple extraction. Firstly, we extract subjects of all possible triples from the sentence, and then identify the corresponding objects under target relations with relation guidance. We utilize relations as prior knowledge instead of regarding relations as classification labels, and apply attention mechanism to obtain fine-grained relation representations, which guide extracted subjects to find the corresponding objects. Our approach (RGAM) can not only learn multiple dependencies in each triple, but also be suitable for extracting implicit relational triples and handling the overlapping triple problem. Extensive experiments show that our model achieves state-of-the-art performance on two public datasets NYT and WebNLG, which demonstrates the effectiveness of our approach.
