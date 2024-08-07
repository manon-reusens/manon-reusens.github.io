---
title: "✅ SEER : A Knapsack approach to Exemplar Selection for In-Context HybridQA"
collection: publications
permalink: /publication/2023-10-01-paper-title-number-3
excerpt: 'This paper introduces a new exemplar selection method named SEER for in-context hybridQA.'
date: 2023-10-01
venue: 'EMNLP'
paperurl: 'https://aclanthology.org/2023.emnlp-main.837/'
citation: 'Tonglet, J., Reusens, M., Borchert, P., & Baesens, B. (2023, December). SEER: A Knapsack approach to Exemplar Selection for In-Context HybridQA. In Proceedings of the 2023 Conference on Empirical Methods in Natural Language Processing (pp. 13569-13583).'
---
Abstract:\\
Question answering over hybrid contexts is a complex task, which requires the combination of information extracted from unstructured texts and structured tables in various ways. Recently, In-Context Learning demonstrated significant performance advances for reasoning tasks. In this paradigm, a large language model performs predictions based on a small set of supporting exemplars. The performance of In-Context Learning depends heavily on the selection procedure of the supporting exemplars, particularly in the case of HybridQA, where considering the diversity of reasoning chains and the large size of the hybrid contexts becomes crucial. In this work, we present Selection of ExEmplars for hybrid Reasoning (SEER), a novel method for selecting a set of exemplars that is both representative and diverse. The key novelty of SEER is that it formulates exemplar selection as a Knapsack Integer Linear Program. The Knapsack framework provides the flexibility to incorporate diversity constraints that prioritize exemplars with desirable attributes, and capacity constraints that ensure that the prompt size respects the provided capacity budgets. The effectiveness of SEER is demonstrated on FinQA and TAT-QA, two real-world benchmarks for HybridQA, where it outperforms previous exemplar selection methods.