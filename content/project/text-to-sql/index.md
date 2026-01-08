---
title: RingSQL - Synthetic Data Generation for Text-to-SQL
date: 2026-01-07
external_link: https://github.com/nu-c3lab/RingSQL
tags:
  - Text-to-SQL
  - Reinforcement Learning
  - Data Generation
---

Recent advances in text-to-SQL systems have been driven by larger models and improved datasets, yet progress is still limited by the scarcity of high-quality training data. Manual data creation is expensive, and existing synthetic methods trade off reliability and scalability. Template-based approaches ensure correct SQL but require schema-specific templates, while LLM-based generation scales easily but lacks quality and correctness guarantees. We introduce RingSQL, a hybrid data generation framework that combines schema-independent query templates with LLM-based paraphrasing of natural-language questions. This approach preserves SQL correctness across diverse schemas while providing broad linguistic variety. In our experiments, we find that models trained using data produced by RingSQL achieve an average gain in accuracy of +2.3% across six text-to-SQL benchmarks when compared to models trained on other synthetic data.

<!--more-->
