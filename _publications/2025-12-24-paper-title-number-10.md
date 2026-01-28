---
title: "🌐 Native Design Bias: Studying the Impact of English Nativeness on Language Model Performance"
collection: publications
permalink: /publication/2025-12-24-paper-title-number-10
excerpt: 'We introduce a novel framework to analyze consistency in persona-assigned LLMs.'
date: 2025-12-24
venue: 'Findings of IJCNLP-AACL'
paperurl: 'https://aclanthology.org/2025.findings-ijcnlp.73/'
publication_type: conference 
citation: 'Manon Reusens, Philipp Borchert, Jochen De Weerdt, and Bart Baesens. 2025. Native Design Bias: Studying the Impact of English Nativeness on Language Model Performance. Proceedings of the 14th International Joint Conference on Natural Language Processing and the 4th Conference of the Asia-Pacific Chapter of the Association for Computational Linguistics, pages 1195–1215, Mumbai, India. The Asian Federation of Natural Language Processing and The Association for Computational Linguistics.'
---
Abstract:\\
Large Language Models (LLMs) excel at providing information acquired during pretraining on large-scale corpora and following instructions through user prompts. However, recent studies suggest that LLMs exhibit biases favoring Western native English speakers over non-Western native speakers. Given English’s role as a global lingua franca and the diversity of its dialects, we extend this analysis to examine whether non-native English speakers also receive lower-quality or factually incorrect responses more frequently. We compare three groups—Western native, non-Western native, and non-native English speakers—across classification and generation tasks. Our results show that performance discrepancies occur when LLMs are prompted by the different groups for the classification tasks. Generative tasks, in contrast, are largely robust to nativeness bias, likely due to their longer context length and optimization for open-ended responses. Additionally, we find a strong anchoring effect when the model is made aware of the user’s nativeness for objective classification tasks, regardless of the correctness of this information. Our analysis is based on a newly collected dataset with over 12,000 unique annotations from 124 annotators, including information on their native language and English proficiency.