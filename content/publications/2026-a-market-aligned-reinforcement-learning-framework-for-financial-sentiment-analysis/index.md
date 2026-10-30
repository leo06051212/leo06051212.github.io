---
title: A Market-Aligned Reinforcement Learning Framework for Financial Sentiment Analysis
authors:
- Zhihang Liu
- Chiu-Wing Sham
- Jiale Li
- me
- Zongcheng Yue
- Chong Fu
date: '2026-06-22T00:00:00Z'
publication_types:
- paper-conference
publication:
  name: 2026 International Joint Conference on Neural Networks (IJCNN)
  pages: 1-8
  publisher: IEEE
abstract: Financial sentiment analysis(FSA) plays a critical role in algorithmic trading
  and market risk assessment. However, most existing approaches define sentiment purely
  through linguistic polarity, ignoring whether such sentiment aligns with actual
  market reactions reflected in price movements. At the same time, commonly used financial
  sentiment datasets and training pipelines are not designed to support the end-to-end
  learning of sentiment signals grounded in market behavior. To address these limitations,
  we propose a market-aligned reinforcement learning(RL) framework for FSA. First,
  we align sentiment with post-news price movements and construct a dataset of over
  16,000 annotated data across short- and medium-term horizons. Second, we develop
  a class-weighted RL algorithm that optimizes model predictions for consistency with
  market-aligned labels. Extensive experiments on both BERT-like models and generative
  models show that our approach consistently outperforms supervised fine-tuning, achieving
  improvements of up to 23% in Macro-F1 and 22% in accuracy. Furthermore, back-testing
  results demonstrate that models trained with our RL framework produce more stable
  and reliable trading signals than semantic sentiment baselines. Our code is publicly
  available.
featured: false
draft: false
requires_correction: false
correction_reasons: []
date_precision: day
publication_date_parts:
- 2026
- 6
- 22
publication_importer:
  managed_citation: true
hugoblox:
  ids:
    doi: 10.1109/ijcnn69854.2026.11729208
links:
- type: source
  url: https://doi.org/10.1109/ijcnn69854.2026.11729208
metadata_review:
  verified_on: '2026-10-30'
  publication_date_source: https://ieeexplore.ieee.org/abstract/document/11729208
  crossref_source: https://api.crossref.org/works/10.1109/ijcnn69854.2026.11729208
---
